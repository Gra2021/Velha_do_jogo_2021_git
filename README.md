# Velha_do_jogo_2021_git

> Jogo da velha em programação em C em aula

# OBJETIVO

Este programa foi desenvolvido em C como parte da disciplina de Linguagem de programação.

## FUNÇÃO main()

- Cria o tabuleiro 3x3 e um inteiro ‘continuar’, que será usado no laço do while que irá controlar se o jogador vai continuar jogando ou não.
- De volta na main, se a opção recebida for 1, ‘continuar’ tem valor lógico TRUE e o jogo prossegue.
- Se a opção recebida for 0, ‘continuar’ tem valor lógico FALSE e o programa termina. 
- Para qualquer outro valor, o laço do while continua a se repetir, até o indivíduo entrar com uma opção válida.
- Note que você pode incrementar esse menu, deixando sempre 0 para sair do jogo. 
- Pode alterar para jogar Humano x Máquina, escolher quem vai ser ‘X’ e quem vai ser ‘O’, quem co-meça e por ai vai.

##  FUNÇÃO MENU ()

- Exibe para usuario a opção  1 jogar e 0 sair.
- Se o jogador escolher 1 ,e poque quer jogar.
- Se o jogador escolher 0(zero)e porque quer sair.

# DESCRIÇÃO

## FUNÇÃO exibetabuleiro()

`char exibetabuleiro( int linha, coluna )`

- Recebe os dados de linhas e colunas e retorna um desenho do tabuleiro na tela com todas as jogadas até o momento.

## FUNÇÃO  checaTermino()

- Que nada mais é que um conjunto de outras funções dentro dela, como

## FUNÇÃO checalinha()

`int checalinha(int tabuleiro[3][3] )`

- Recebe o tabuleiro e verifica se algum jogador completou uma linha inteira.

## FUNÇÃO  checaColuna() 

-  Faz a mesma coisa da função anterior, mas checa as colunas.

## FUNÇÃO checa diagonal ()

- Essa função checa as duas diagonais de nosso tabuleiro, pra ver se a soma de uma delas é 3 ou -3.
-  Se alguma das funções anteriores acusar soma 3 ou -3, elas retornam valor 1 (TRUE), então o teste condiciona if é acionado, a mensagem de vitória é dada e a função retorna valor 1, dizendo que o jogo terminou.

##FUNÇÃO checaEmpate()

- Checa se ainda existe alguma casa livre no tabuleiro. Ou seja, ela sai em busca do número 0, que representa casa vazia, se encontrar retorna valor lógico FALSE, indicando que não foi empate.
-  Porém, se não encontrar 0, é porque o tabuleiro está preenchido e ela retorna valor 1 e a men-sagem de empate.












