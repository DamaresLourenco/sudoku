# 🧠 Sudoku em Java

Projeto prático de um jogo de Sudoku desenvolvido em Java como parte do desafio da Digital Innovation One (DIO). Este projeto tem como objetivo reforçar conceitos de Programação Orientada a Objetos (POO), como:

- Abstração
- Encapsulamento
- Herança
- Polimorfismo

---

## 🎯 Objetivo

Criar um jogo de Sudoku funcional utilizando Java, aplicando os fundamentos da orientação a objetos, lógica de programação e estruturação de código limpo.

---

## 💻 Tecnologias

- Java 11+
- Programação Orientada a Objetos
- Git e GitHub

---

## 🚀 Como Executar

### Requisitos:

- Java JDK 11 ou superior instalado
- IDE Java (IntelliJ, Eclipse, VSCode) ou terminal configurado

### Passo a passo:

1. Clone o repositório:
```bash
git clone https://github.com/DamaresLourenco/sudoku.git
```
2. Compile os arquivos:
```bash
javac Main.java
```
3. Execute o programa com os argumentos do Sudoku:
```bash
java Main "0,0;4,false 1,0;7,false 2,0;9,true 3,0;5,false 4,0;8,true 5,0;6,true 6,0;2,true 7,0;3,false 8,0;1,false 0,1;1,false 1,1;3,true 2,1;5,false 3,1;4,false 4,1;7,true 5,1;2,false 6,1;8,false 7,1;9,true 8,1;6,true 0,2;2,false 1,2;6,true 2,2;8,false 3,2;9,false 4,2;1,true 5,2;3,false 6,2;7,false 7,2;4,false 8,2;5,true 0,3;5,true 1,3;1,false 2,3;3,true 3,3;7,false 4,3;6,false 5,3;4,false 6,3;9,false 7,3;8,true 8,3;2,false 0,4;8,false 1,4;9,true 2,4;7,false 3,4;1,true 4,4;2,true 5,4;5,true 6,4;3,false 7,4;6,true 8,4;4,false 0,5;6,false 1,5;4,true 2,5;2,false 3,5;3,false 4,5;9,false 5,5;8,false 6,5;1,true 7,5;5,false 8,5;7,true 0,6;7,true 1,6;5,false 2,6;4,false 3,6;2,false 4,6;3,true 5,6;9,false 6,6;6,false 7,6;1,true 8,6;8,false 0,7;9,true 1,7;8,true 2,7;1,false 3,7;6,false 4,7;4,true 5,7;7,false 6,7;5,false 7,7;2,true 8,7;3,false 0,8;3,false 1,8;2,false 2,8;6,true 3,8;8,true 4,8;5,true 5,8;1,false 6,8;4,true 7,8;7,false 8,8;9,false"
```
## 📌 Argumento do Sudoku

O argumento consiste em valores de coordenadas, número e se o valor é fixo ou não:

```vbnet
formato: coluna,linha;valor,fixed
exemplo: 0,0;4,false → posição (0,0), valor 4, não fixo
```

Use o comando acima com o argumento completo para executar o jogo. 

## 🧠 Conceitos POO Utilizados
●Abstração: representação de células, tabuleiro e lógica do jogo.

●Encapsulamento: atributos privados com acesso controlado.

●Herança: possibilidade de criar extensões futuras (ex: modos de jogo).

●Polimorfismo: estrutura para diferentes comportamentos dos métodos. 

## 📁 Estrutura do Projeto
sudoku/

├── Main.java

├── SudokuBoard.java

├── Cell.java

├── README.md

## 📚 Fontes
Desafio DIO:[https://github.com/digitalinnovationone/sudoku]

Branch UI (interface gráfica): [https://github.com/digitalinnovationone/sudoku/tree/ui]

## 🙋‍♀️ Autora
Desenvolvido o Readme por Damares Lourenço 💡
