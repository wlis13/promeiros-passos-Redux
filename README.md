# promeiros-passos-Redux

Aqui temos um objeto com duas chaves
a primeira é um array com nomes de cores
e a outra é do tipo number que inicia com
o número zero, na próxima etapa usei dois
botões cada um com um evento de click,
sendo que em cada evento foi atribuído
 o valor de uma variável no parâmetro action
(em cada evento uma variável diferente), e
também em cada evento o valor da chave Index é
modificado através da função Math.random() que
atribui um valor sorteado de 0 á 5 na chave index.
  Na próxima etapa foi feito o uso do reducer()
em que esse uso consiste em uma condição que
verifica qual é o valor da action, más ambos os
valores vão receber o valor da chave colors com o
valor do índice correspondente ao valor da chave index que
como dito acima é um valor sorteado.
  Com isso o store a cada clique vai receber uma valor
do arrau colors sorteado e então na função subscribe()
esse mesmo valor que após o clique vai ser inserido no srore
vai também modificar o stilo do backgroundColor da página.
