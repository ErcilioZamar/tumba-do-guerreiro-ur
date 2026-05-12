# 🏺 A Tumba do Guerreiro Ur

Um jogo roguelike desenvolvido em Python utilizando Pygame, onde o jogador explora uma sequência infinita de portas em busca da lendária Tumba do Guerreiro Ur.

---

## 🎮 Sobre o jogo

O jogador deve atravessar portas aleatórias, enfrentando sistemas de risco como:

- Portas falsas que fazem o jogador regredir
- Sistema de permadeath progressivo
- Biomas aleatórios gerados dinamicamente
- Sistema de checkpoint salvo em arquivo
- Possibilidade de encontrar a Tumba do Guerreiro Ur

---

## ⚙️ Mecânicas principais

### 🚪 Exploração de portas
Cada escolha leva o jogador a novos caminhos gerados aleatoriamente.

### 🌍 Biomas dinâmicos
O jogo gera diferentes ambientes como:
- Florestas
- Montanhas
- Cavernas
- Lagos
- Desertos

### ☠️ Permadeath progressivo
Após a porta 2000, o sistema ativa penalidades permanentes no progresso.

### 💾 Sistema de salvamento
O progresso do jogador é salvo automaticamente em arquivo JSON.

### 🎵 Trilha sonora
Música ambiente em loop para imersão.

---

## 🛠️ Tecnologias utilizadas

- Python
- Pygame
- JSON (save system)
- Random
- OS / SYS

---

## ▶️ Como executar

### 1. Clone o repositório
```bash
git clone URL_DO_REPO
cd tumba-do-guerreiro-ur
```
### 2. Instale as dependências
pip install pygame

### 3. Execute o game
python main.py

⚠️ Observações importantes
O jogo depende de Pygame instalado corretamente
O arquivo de música deve estar na mesma pasta (musica_alem.mp3)
O sistema de checkpoint salva em checkpoint.json


📌 Conceitos aplicados
Este projeto demonstra:
Programação orientada a eventos
Geração procedural de conteúdo
Sistemas de estado e progressão
Persistência de dados (save system)
UI simples com Pygame
Lógica de jogo (game loop)


👨‍💻 Autor
Desenvolvido por Ercilio Zamar
Estudante de Análise e Desenvolvimento de Sistemas com foco em Python, automação e desenvolvimento de jogos.
