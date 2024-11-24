# Calculadora Simples com Qt e C++

Este repositório contém uma **calculadora simples desenvolvida em C++ utilizando o Qt Framework**. O objetivo do projeto é demonstrar a construção de uma aplicação GUI (Interface Gráfica do Usuário) utilizando os conceitos de **orientação a objetos** e **boas práticas de programação**.

## 🛠 Funcionalidades

- Interface gráfica amigável e interativa.
- Suporte a operações básicas: `+`, `-`, `*`, `/`.
- Limpeza do display para iniciar novos cálculos.
- Implementação modular com separação entre lógica de cálculo e interface gráfica.

## 📂 Estrutura do Projeto

O projeto está organizado nos seguintes arquivos principais:

### Classes
- **`Calculadora`**: Gerencia a lógica de cálculo.
  - **Arquivos**: `calculadora.h` e `calculadora.cpp`
  - Realiza as operações matemáticas de forma eficiente e segura.
- **`MainWindow`**: Responsável pela interface gráfica e interação com o usuário.
  - **Arquivos**: `mainwindow.h`, `mainwindow.cpp` e `mainwindow.ui`
  - Controla os eventos dos botões e atualiza o display.

### Arquivo Principal
- **`main.cpp`**: Ponto de entrada do programa.

## 🧱 Tecnologias Utilizadas

- **C++**: Linguagem base para o desenvolvimento.
- **Qt Framework**: Ferramenta para criação de interfaces gráficas e gerenciamento de eventos.

## 🚀 Como Executar

### Pré-requisitos:
1. Instale o [Qt Creator](https://www.qt.io/product/development-tools) em sua máquina.
2. Configure o ambiente para suportar projetos com C++.

### Passos:
1. Clone este repositório:
   ```bash
   git clone https://github.com/18carica/Projeto-Qt-CPP-Calculadora
   ```
2.  Abra o projeto no Qt Creator.  

3.  Compile e execute para testar a calculadora.  

## 🔧 Personalizações Futuras

- Adicionar suporte a operações científicas (ex.: potências, raízes, seno, cosseno).  
- Melhorar a interface gráfica com temas personalizados.  
- Implementar testes automatizados para garantir maior robustez.  

## 📝 Licença

Este projeto é licenciado sob a **MIT License**. Sinta-se à vontade para utilizá-lo, modificá-lo e compartilhá-lo.
