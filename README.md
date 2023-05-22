# Grids
Você foi contratado pelo mago mais famoso do planeta a vencer um jogo, trata-se de Harry
Potter! Harry recebe um grid mágico S com R linhas e C colunas contendo a localização de um
artefato poderoso, O objetivo do jogo é levar Harry a este artefato sem deixar sua energia cair a 0.
Cada célula do grid possui ou uma poção ou um monstro. Um monstro na célula (i,j) retira S[i][j]
de energia de Harry, enquanto uma poção na célula (i,j) aumenta a energia de Harry em S[i][j]. Se
Harry ficar com 0 de energia ou menos ele morre e Voldemort ficará indestrutível!
A jornada de Harry sempre começa na célula (1,1) e o artefato sempre está na célula (R,C). De
uma célula (i,j) Harry pode se movimentar apenas para baixo (i+1, j) ou para direita (i, j+1) e não
pode se mover para fora do grid mágico. Sua tarefa é definir qual seria a energia mínima de Harry
na célula (1,1) para ele continuar com uma energia positiva ao longo de sua jornada até a célula
(R, C).

A primeira linha do arquivo de entrada contem um inteiro T indicando o número de casos de
testes. Cada caso de teste consiste em R e C na primeira linha seguido pela descrição do grid em
R linhas, cada uma contendo C inteiros. As linhas são numeradas de 1 a R de cima para baixo
e as colunas são numeradas de 1 a C da esquerda para a direita. Células com S[i][j] < 0 contêm
monstros, outras contêm poções mágicas.

Exemplo de entrada:

3

2 3

0 1 -3

1 -2 0

2 2

0 1

2 0

3 4

0 -2 -3 1

-1 4 0 -2

1 -2 -3 0

Exemplo de saída:

2

1

2

Grid de exmplo:

![grid1](https://github.com/Arthur99Silva/Grids/assets/51514914/bd644841-ccad-4940-a140-581dd13e9bcf)

Caminho mínimo:

![Minimo1](https://github.com/Arthur99Silva/Grids/assets/51514914/19d7b17c-b2e6-42e1-bc14-6cf269f9d324)
