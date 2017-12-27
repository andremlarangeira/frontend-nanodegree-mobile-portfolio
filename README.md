**Mobile portfolio**
=============================


Instruções:
----------------------------

- Para executar o teste execute o arquivo *index.html*

- No arquivo index.html foi retirado o link da font do GoogleFonts, adicionado os
  media queries nos links do css e adicionado o async na chamada do script js/perfmatters.js.

- No arquivo views/js/main.js, foi retirado a criação das funções de dentro da função
  resizePizzas, na funcão changePizzaSizes foi criada uma variavel pizzas para receber
  o valor de document.querySelectorAll(".randomPizzaContainer") para evitar querySelectorAll
  o script busque redundantemente as divs que serão dimensionadas. O calculo das variaveis
  dx e newwidth foram retiradas de dentro do loop para evitar o Forced Synchronous Layout.
