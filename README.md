Batalha Naval - Jogo em Python com PyGame

Um jogo clássico de Batalha Naval implementado em Python com interface gráfica usando PyGame.

https://screenshot.png

Funcionalidades
Menu principal com interface amigável

Dois modos de jogo: Player vs Player e Player vs Bot

Sistema de posicionamento de navios intuitivo

IA para o modo single player

Interface gráfica colorida e responsiva

Detecção de navios afundados

Animações e efeitos visuais

Requisitos
Python 3.8 ou superior

Biblioteca PyGame

Instalação
Clone o repositório ou baixe o arquivo Batalha_naval.py:

bash
git clone https://github.com/Laurentx1/Batalha-naval.git
cd batalha-naval
Instale a biblioteca PyGame (se ainda não tiver):

bash
pip install pygame
Execute o jogo:

bash
python Batalha_naval.py
Como Jogar
Modo Player vs Player
Escolha o modo "Player vs Player" no menu

Cada jogador posiciona seus navios no tabuleiro

Os jogadores alternam turnos para tentar afundar a frota adversária

Vence quem afundar todos os navios do oponente primeiro

Modo Player vs Bot
Escolha o modo "Player vs Bot" no menu

Posicione seus navios no tabuleiro

O bot posicionará seus navios automaticamente

Alternne turnos com o bot até que uma frota seja completamente afundada

Posicionamento de Navios
Clique em um navio na lista à direita para selecioná-lo

Clique no tabuleiro para posicionar o navio

Use o botão "Orientação" para alternar entre horizontal e vertical

Todos os navios devem ser posicionados antes de iniciar o jogo

Durante o Jogo
Clique no tabuleiro do adversário para atacar

Acertos são marcados em vermelho

Erros são marcados em branco

Navios afundados são destacados
Estrutura do Projeto
text
batalha_naval.py  # Arquivo principal do jogo
README.md         # Este arquivo
Classes Principais
Game: Gerencia o estado do jogo e a lógica principal

Player: Representa um jogador (humano ou bot) com seu tabuleiro e frota

Ship: Representa um navio com nome, tamanho e estado (atingido/afundado)

GameState: Enumeração dos estados possíveis do jogo

Regras do Jogo
Cada jogador tem uma frota de 5 navios de diferentes tamanhos

Os navios não podem se sobrepor ou ser posicionados fora do tabuleiro

Os jogadores alternam turnos para realizar ataques

Um navio é afundado quando todas as suas partes são atingidas

O jogo termina quando todos os navios de um jogador são afundados

🔧 Personalização
Você pode personalizar o jogo modificando as constantes no início do código:

BOARD_SIZE: Tamanho do tabuleiro (padrão: 10x10)

CELL_SIZE: Tamanho de cada célula em pixels

SHIP_TYPES: Tipos e tamanhos dos navios

Cores e fontes para personalizar a aparência

Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para:

Fazer um fork do projeto

Criar uma branch para sua feature (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abrir um Pull Request

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Reportar Problemas
Encontrou um bug ou tem uma sugestão? Por favor, abra uma issue no GitHub.

