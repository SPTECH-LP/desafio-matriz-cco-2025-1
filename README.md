# Mini-Jogo "Caça ao Tesouro" em JavaScript
## 🚩 Objetivo:
Criar um jogo simples em JavaScript onde o jogador deve encontrar tesouros escondidos em um mapa bidimensional (matriz), utilizando conceitos de matrizes para gerenciar as posições dos tesouros e das armadilhas.

## 📄 Descrição da Atividade:

### Introdução ao Jogo:
O mapa do jogo é representado por uma matriz de duas dimensões, onde cada posição pode conter um tesouro, uma armadilha ou estar vazia. O objetivo é encontrar todos os tesouros sem cair nas armadilhas.

### 📄 Especificação do Jogo:

### Mapa:
Uma matriz de inteiros onde cada elemento representa uma posição no mapa. Valores específicos indicam tesouros, armadilhas ou espaços vazios.

### Jogadas:
O jogador escolhe uma posição na matriz (linha e coluna) para "escavar" em busca de tesouros.
Se a posição contiver um tesouro, o jogador ganha pontos.
Se for uma armadilha, o jogo termina para o jogador.

### Partidas e Pontuação:
O jogo terá 3 partidas (um jogador por partida).
O jogador acumula pontos por cada tesouro encontrado.
A partida termina quando todos os tesouros forem encontrados ou o jogador acionar uma armadilha.

### Vencedor:
Após as 3 partidas, o jogo deve indicar quem ficou em primeiro, segundo e terceiro lugar.

## 🏆 Desafios de Programação:

### ✅ Inicialização do Mapa:
Gerar aleatoriamente as posições dos tesouros e das armadilhas na matriz.

### ✅ Lógica do Jogo:
Implementar a lógica para verificar as escolhas do jogador, atualizar o mapa e a pontuação, e determinar o fim da partida.

### ✅ Interface com o Usuário:
Desenvolver uma interface para permitir que o jogador escolha as posições (linha e coluna) e para mostrar o estado atual do jogo.
