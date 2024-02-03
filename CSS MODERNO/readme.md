## Responsividade

A responsividade é a capacidade de uma página web se adaptar automaticamente para diferentes tamanhos de tela, seja celular, tablet ou desktop. Este módulo terá 3 aulas dedicadas à responsividade:

- **Visão geral**: Aula introdutória e mais teórica explicando o conceito de responsividade e como testá-la na prática.
- **Media Queries**: A funcionalidade que permite criar layouts responsivos no CSS. Será explicado como utilizar media queries para modificar estilos conforme a largura da tela.
- **Mobile First**: Abordagem de desenvolvimento onde se cria primeiramente a versão mobile de um site para depois expandir para desktop. Iremos aplicar essa boa prática na prática.

## Flexbox

O Flexbox é um método de organização e alinhamento de elementos dentro de containers flexíveis. Por ser um tópico mais complexo, teremos uma grade com mais aulas sobre Flexbox, divididas da seguinte forma:

- **O que é e para que serve**: Aula introdutória e teórica.
- **Criação de layout**: Iremos criar um layout simples de estudos que servirá de base para aplicarmos os conceitos de Flexbox posteriormente.
- **Manipulação do Flex Container**: Aprenderemos a mexer em configurações como direction, gap, justify-content e align-items.
- **Exercício de fixação**: Praticaremos o que aprendemos na aula anterior.
- **Manipulação dos Flex Items**: Verificaremos opções como flex-basis, flex-grow, flex-shrink, order e align-self.
- **Exercício de Flexbox**: Desafio final englobando todos os conceitos estudados no módulo.
- **Resolução do exercício**: Explicação da resolução do exercício anterior.

## CSS Grid

Assim como o Flexbox, o CSS Grid também serve para organizar layouts de páginas web. Em alguns casos, pode-se usar os dois em conjunto. Novamente, teremos aulas similares às do Flexbox:

- **O que é e para que serve**
- **Modificação do layout**: Transformaremos o layout de estudos criado com Flexbox para usar Grid Layout.
- **Manipulação do Grid Container**: Propriedades como grid-template-columns, gap, grid-template-rows.
- **Exercício de fixação**
- **Manipulação de linhas e colunas**: grid-column, grid-row, grid-template-areas.
- **Exercício Grid e Flexbox**: Desafio final usando Grid e Flexbox.
- **Resolução do exercício**
- **Conclusão**: Revisão de tudo o que foi estudado.

## Visão geral sobre responsividade

A responsividade web surgiu da necessidade de adaptação dos sites para diferentes dispositivos que pessoas utilizam para acessar a internet, como celulares, tablets e desktops. Cada tipo de dispositivo possui características únicas de tamanho de tela, resolução, métodos de entrada de dados, capacidade de processamento, entre outros. Por isso, se um site não for responsivo, a experiência de uso pode ficar comprometida em alguns dispositivos. Por exemplo, em uma tela pequena de celular, um site com layout fixo e largo seria inconveniente de usar, exigindo dar zoom e rolar a página horizontalmente. Já um site responsivo se adapta automaticamente, reorganizando seus elementos para aproveitar da melhor forma o espaço disponível em qualquer tela.

## Como funciona a responsividade?

A responsividade web baseia-se principalmente no uso de 3 técnicas:

- **Media Queries**: Permite aplicar regras CSS diferentes conforme o tamanho da tela.
- **Layouts flexíveis**: Uso de unidades relativas como % ou vw ao invés de valores fixos como px.
- **Imagens flexíveis**: Imagens adaptam seu tamanho máximo conforme a largura do container.

Combinando essas técnicas, conseguimos fazer com que o layout de uma página mude dinamicamente de acordo com o espaço disponível.