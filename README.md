# Sudoku Java

Projeto de implementação do jogo **Sudoku** em Java, seguindo boas práticas de programação.

---

## 📝 Descrição

Este projeto consiste em um jogo de Sudoku totalmente funcional, permitindo:

* Criar tabuleiros de Sudoku.
* Inserir números no tabuleiro.
* Validar jogadas.
* Resolver o tabuleiro automaticamente usando algoritmo de backtracking.

O código foi organizado em camadas seguindo o princípio **Single Responsibility**, tornando-o modular, fácil de manter e estender.

---

## 📦 Estrutura do Projeto

```
sudoku/
├── model/            # Classes do modelo: Board, Cell
├── solver/           # Lógica de resolução: Solver, BacktrackingSolver
├── game/             # Controle do jogo: SudokuGame
├── io/               # Entrada e saída: InputHandler, OutputHandler
└── Main.java         # Classe principal para rodar o jogo
```

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/clebergomesjr/sudoku.git
cd sudoku
```

2. Compile o projeto (Maven):

```bash
mvn clean install
```

3. Rode a aplicação:

```bash
mvn exec:java -Dexec.mainClass="Main"
```

---

## 🛠 Funcionalidades

* Preencher números no tabuleiro.
* Validar se a jogada é válida.
* Resolver automaticamente o Sudoku com \*\*backt
