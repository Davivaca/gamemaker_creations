# gamemaker_creations

## Jogo plataforma

### Primeiro vídeo: Movimentação e colisão

#### Sprite
Crie um sprite na parte de sprite e coloque a colisão na parte central inferior
Faça o mesmo para a parede, crie um sprite e um objeto respectivamente

#### Criando o código
Crie um script create no objeto player
Crie uma variável chamada direita e outra chamada esquerda no objeto player
Crie um script step no objeto player

Crie duas variaveis para direita e esquerda e então coloque a velocidade horizontal como resultado de direita menos esquerda vezes velocidade
Depois disso use a variável x para receber o resultado da velocidade horizontal
A partir desse momento já deve ser poissível movimentar o objeto jogador em seu jogo rodando

#### Colisão
No objeto player crie uma variável para a velocidade vertical
No obj player crie um if para prever se o player vai colidir com a parede

Crie um while dentro do if com placemeet x + sign da velocidade horizontal
o que é um sign? Uma função que indica se alguma variável é negativa positiva ou zero com o retorno sendo: 1, -1 ou 0
Coloque o x recebendo o valor de sign da velocidade horizontal e fora do while a velocidade horizontal recebe 0

Agora devemos fazer o mesmo para a velocidade vertical

#### Gravidade e Pulo
Comece criando duas variáveis em criar: "Cima" e "gravidade"
Crie um keyboard check para o botão de "Cima"
Você tem que criar um if para quando não estiver acontecendo uma colisão para poder fazer a gravidade funcionar

### Segundo vídeo: Sprites e sistema de vida
Primeiro crie os sprites

#### Importando e editando
Crie um sprite para a animação de ficar parado e importe o sprite que você fez
Depois clique em editar imagem - imagem - Converter em frames

Crie uma variável para a direção do player e depois use essa variável para alterar os sprites do personagem

#### Vida
Primeiro vá no player e crie uma variável vida

# PAREI NO VÍDEO 2 minuto 13:00
