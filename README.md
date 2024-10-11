---

# 📊 Simulador de Gerenciamento de Processos

Este projeto é uma simulação de gerenciamento de processos, desenvolvido no contexto da disciplina de **Sistemas Operacionais**. O código é escrito em C e implementa um algoritmo de escalonamento de processos utilizando filas. A aplicação gerencia a execução de processos através de uma abordagem de preempção com um quantum de tempo.

## 📑 Índice
1. [Objetivos](#-objetivos)
2. [Funcionalidades](#%EF%B8%8F-funcionalidades)
3. [Tecnologias Utilizadas](#-tecnologias-utilizadas)
4. [Pré-requisitos](#-pré-requisitos)
5. [Instalação](#-instalação)
6. [Autor](#-autor)

## 🎯 Objetivos
- Simular o gerenciamento de processos utilizando filas.
- Implementar um algoritmo de escalonamento baseado em quantum de tempo.
- Demonstrar a adição, execução e finalização de processos em um ambiente controlado.

## ⚙️ Funcionalidades
- **Enfileiramento de Processos**: Permite adicionar processos à fila de prontos.
- **Desenfileiramento de Processos**: Remove processos da fila de prontos para execução.
- **Execução de Processos**: Processos são executados até o término ou até que o quantum expire, resultando em preempção.
- **Exibição do Estado das Filas**: Mostra o estado atual das filas de processos, incluindo filas de prontos, espera, execução e finalizados.

## 🛠 Tecnologias Utilizadas
- **C**: Linguagem de programação utilizada para desenvolver a aplicação.
- **Compilador GCC**: Compilador utilizado para compilar o código.

## 📝 Pré-requisitos
Para executar este projeto, você precisará de:
- Um compilador C (como GCC).
- IDE ou editor de texto de sua escolha (ex: Code::Blocks, Visual Studio Code).

## 🚀 Instalação
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/smuelp/states-process.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd states-process
   ```

3. **Compile o código:**
   ```bash
   gcc -o simulador main.c
   ```

4. **Execute a aplicação:**
   ```bash
   ./simulador
   ```

## 👤 Autor
Desenvolvido por _Samuel Ildebrando Pena._

---
