# Trabalho Introdução ao Python

<h2>Nível de Gama</h2>

O que é a gama?

Gama pode ser caracterizada como a fluidez entre o preto e o branco na tela. A gama aumenta ou diminui a diferença entre as áreas claras e escuras, aumentando, a imagem se torna mais escura, e ao diminuir a imagem se torna mais clara. A gama tem diversas curvas, sendo as mais comuns a 2.2 e 2.4 e esse número representa a curvatura da curva de preto para branco ou de branco para preto. Além dessas curvas, outras comumente usadas são a 1.8, 2.0, 2.6.

Como Está Implementado no código

O código pega todos os pixels da imagem em um array e eleva eles pelo valor da gama selecionado, no exemplo está como 0.1, usando a fórmula: brilho = (sinal) ** gamma,
no código temos a variável c, que é responsável por identificar todos os pixels da imagem e temos o código de saída, onde ele multiplica a variável c por 255 e aplica a fórmula do brilho do gamma, definindo o tipo da variável como uint8 que varia entre 0 e 255, por isso as multiplicações por esse número.
