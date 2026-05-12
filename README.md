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
