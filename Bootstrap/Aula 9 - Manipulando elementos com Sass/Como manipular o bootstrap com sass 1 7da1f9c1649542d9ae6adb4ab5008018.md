# Como manipular o bootstrap com sass 1

1. Primeiramente você vai fazer a inicialização da sua aplicação com o npm, utilizando:

   ```sass
   npm init -y
   ```

2. Logo em seguida, vamos fazer a instalação do boostrap, só que dessa vez através do npm, não com o link.

   ```sass
   npm install bootstrap
   ```

3. Se você tem já o sass instalado, não precisa fazer mais nada, com isso, temos aqui uma pasta chamada node_modules e dentro dela temos o css e o js do bootstrap!
4. Você precisa fazer um link de um css, então você vai fazer com que no head nós tenhamos um link, com isso, precisamos linkar o bootstrap padrão com o caminho dele, mesma coisa com o JS.
5. Nós vamos de teste colocar um botão primary, e vamos fazer a mudança da cor dele, vamos ter dentro de node_modules uma pasta chamada scss, vamos no arquivo de variables e vamos fazer a mudança da cor azul, com isso, vamos conseguir alterar a cor primaria.
6. E para alterar, vamos fazer exatamente a mesma coisa que sempre fizemos com sass, apenas mudando agora os endereços tanto do sass quanto do css.

   ```sass
   npx sass --watch ./node_modules/bootstrap/scss:node_modules/bootstrap/dist/css
   ```

   _Se der errado verifique se o sass foi instalado no projeto._

7. Com esse comando, estamos criando uma nova pasta e fazendo isso vamos ter que redirecionar o caminho css, isso fica mais fácil para nós fazermos as demais compilações.

_Dica 1_
Sempre iremos manipular o variables.scss,pois nele temos as variaveis em Sass que manipulam o Bootstrap. Além disso sempre a;terar a variavel que esta sendo recebida pela classe

_Dica 2_
Na documentação do bootstrap tem a parte de manipulacao com sass. a coluna da esquerda sao as classes e a coluna da direita sao as variaveis ou os valores. Sao esses ultimos que posso alterar no meu core do bootstrap.

Aqui está um exemplo de manipulacao sass para os componentes botoes

$btn-padding-y:               $input-btn-padding-y;
$btn-padding-x: $input-btn-padding-x;
$btn-font-family: $input-btn-font-family;
$btn-font-size: $input-btn-font-size;
$btn-line-height: $input-btn-line-height;
$btn-white-space: null; // Set to `nowrap` to prevent text wrapping

$btn-padding-y-sm:            $input-btn-padding-y-sm;
$btn-padding-x-sm: $input-btn-padding-x-sm;
$btn-font-size-sm: $input-btn-font-size-sm;

$btn-padding-y-lg:            $input-btn-padding-y-lg;
$btn-padding-x-lg: $input-btn-padding-x-lg;
$btn-font-size-lg: $input-btn-font-size-lg;

$btn-border-width: $input-btn-border-width;

$btn-font-weight:             $font-weight-normal;
$btn-box-shadow: inset 0 1px 0 rgba($white, .15), 0 1px 1px rgba($black, .075);
$btn-focus-width:             $input-btn-focus-width;
$btn-focus-box-shadow: $input-btn-focus-box-shadow;
$btn-disabled-opacity: .65;
$btn-active-box-shadow:       inset 0 3px 5px rgba($black, .125);

$btn-link-color:              $link-color;
$btn-link-hover-color: $link-hover-color;
$btn-link-disabled-color: $gray-600;

// Allows for customizing button radius independently from global border radius
$btn-border-radius:           $border-radius;
$btn-border-radius-sm: $border-radius-sm;
$btn-border-radius-lg: $border-radius-lg;

$btn-transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;

$btn-hover-bg-shade-amount:       15%;
$btn-hover-bg-tint-amount: 15%;
$btn-hover-border-shade-amount:   20%;
$btn-hover-border-tint-amount: 10%;
$btn-active-bg-shade-amount:      20%;
$btn-active-bg-tint-amount: 20%;
$btn-active-border-shade-amount:  25%;
$btn-active-border-tint-amount: 10%;
