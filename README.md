# FlexboxParte1

## sumário:
- justify-content
- align-items
- flex-direction
- order
- align-self
- flex-wrap
- flex-flow
- align-content



## justify-content: que alinha itens horizontalmente, e aceita os seguintes valores:

- flex-start: Itens se alinham à esquerda do container.
- flex-end: Itens se alinham à direita do container.
- center: Itens se alinham no centro do container.
- space-between: Itens se alinham com distância igual entre eles.
- space-around: Itens se alinham com distância igual em torno deles.
Por exemplo, justify-content: flex-end; moverá o item para a direita.


## align-items: alinha os itens verticalmente e aceita os seguintes valores:

	* flex-start: Itens se alinham na parte de cima do container.
	* flex-end: Itens se alinham na parte de baixo do container.
	* center: Itens se alinham no centro vertical do container.
	* baseline: Items se alinham na linha da base do container.
	* stretch: Itens se esticam para preencher o container.
	Por exemplo, align-items: flex-end;


## align-content: para definir como múltiplas linhas devem ser espaçadas uma das outras. 
 recebe os seguintes valores:

	* flex-start: Linhas são agrupadas no topo do container.
	* flex-end: Linhas são agrupadas no fundo do container.
	* center:Linhas são agrupadas no centro vertical do container.
	* space-between: Linhas são posicionadas com espaço igual entre elas.
	* space-around: Linhas são posicionadas com espaço igual em torno delas.
	* stretch: Linhas se esticam para preencher o container.

align-content determina o espaçamento entre linhas, 
align-items determina como as linhas como um todo são alinhadas dentro do container. 
Quando há só uma linha, align-content não tem nenhum efeito.


## flex-direction: define a direção em que os itens são posicionados no container e aceita os seguintes valores:

	* row: Itens são posicionados na mesma direção do texto.
	* row-reverse: Itens são posicionados na direção oposta à do texto.
	* column: Itens são posicionados de cima para baixo.
	* column-reverse: Itens são posicionados de baixo para cima.
	Por exemplo, flex-direction: row;


## order: determina o lugar onde os elementos apareceraõ, reordenar os itens de acordo com seus conteudos.

	Às vezes, reverter a ordem de uma coluna, ou de um container, não é suficiente. 
	Nesses casos, podemos aplicar a propriedade order, para itens individuais.
	Por padrão, itens tem um valor de 0, mas nós podemos usar essa propriedade 
	para alterar para um valor inteiro positivo ou negativo(+ou-).
	Por exemplo, order: -1;


## align-self: aceita os mesmos valores que align-items, e seus valores são usados para o item específico.
 
	* flex-start: apenas o item se alinha na parte de cima do container.
	* flex-end: apenas o item sese alinha na parte de baixo do container.
	* center: apenas o item se alinha no centro vertical do container.
	* baseline: apenas o item se alinha na linha da base do container.
	* stretch: apenas o item se estica para preencher o container.
	Por exemplo, align-items: flex-end;
 
 
## flex-wrap: Espalhe-os os itens apertados em uma unica linha que aceita os seguintes valores:
	* nowrap: Todos os itens são apertados em uma única linha.
	* wrap: Itens se separam em linhas adicionais.
	* wrap-reverse: Itens se separam em linhas adicionais em reverso.
	Por exemplo, flex-wrap: wrap; 
 
 
## flex-flow: aceita o valor das duas propriedades separados por um espaço.
	As duas propriedades flex-direction e flex-wrap são usadas tão frequentemente juntas que uma 
	propriedade abreviada flex-flow foi criada para combiná-las.

	Por exemplo, flex-flow: row wrap; (para aplicar a direção de linha e quebrar em múltiplas linhas).

