![Python](https://img.shields.io/badge/Python-3.11-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-green)
![CSV](https://img.shields.io/badge/CSV-Database-orange)
![Desktop](https://img.shields.io/badge/Desktop-Application-purple)
![Status](https://img.shields.io/badge/status-concluded-success)

# 🎬 Sistema de Locadora de Filmes // Projeto Final Introdução a Programação

> **Aplicação desktop desenvolvida em Python para gerenciamento de uma locadora de filmes utilizando arquivos CSV como persistência de dados.**

Este projeto simula o funcionamento de uma locadora de filmes, permitindo consultar o catálogo, cadastrar novos filmes, realizar locações, devolver filmes, remover títulos e receber recomendações personalizadas com base no gênero e na classificação indicativa.

Toda a interface foi construída utilizando **Tkinter**, enquanto os dados são armazenados em um arquivo **CSV**, dispensando o uso de bancos de dados.

---

## ✨ Funcionalidades

- 🎞️ Visualização do catálogo completo
- 🔍 Busca de filmes pelo título
- ➕ Cadastro de novos filmes
- ❌ Remoção de filmes do catálogo
- 📦 Locação de filmes
- ↩️ Devolução de filmes
- ⭐ Recomendação personalizada por gênero e classificação indicativa
- 💾 Armazenamento permanente em arquivo CSV

---

## 🧩 Tecnologias Utilizadas

- Python 3
- Tkinter
- CSV
- Programação Procedural

---

## ⚙️ Funcionamento

O sistema utiliza um arquivo chamado **filmes.csv** para armazenar todas as informações dos filmes.

Cada registro possui os seguintes campos:

- Título
- Classificação Indicativa
- Gênero
- Sinopse
- Status (disponível ou alugado)

Sempre que um filme é cadastrado, alugado, devolvido ou removido, o arquivo CSV é atualizado automaticamente.

---

## 📋 Operações Disponíveis

### 🔍 Buscar Filme

Permite pesquisar um filme pelo título e visualizar:

- título;
- classificação indicativa;
- gênero;
- sinopse;
- disponibilidade para locação.

---

### 📦 Locar Filme

Ao localizar um filme disponível, seu status é alterado para **alugado**, impedindo novas locações até que seja devolvido.

---

### ↩️ Devolver Filme

Altera o status do filme de **alugado** para **disponível**, tornando-o novamente disponível para locação.

---

### ➕ Cadastrar Filme

Permite adicionar novos filmes ao catálogo informando:

- título;
- classificação indicativa;
- gênero;
- sinopse.

Todo novo filme é cadastrado automaticamente como **disponível**.

---

### ❌ Remover Filme

Exclui permanentemente um filme do catálogo.

---

### ⭐ Recomendação Personalizada

O usuário pode selecionar:

- classificação indicativa;
- gênero.

O sistema procura até **dois filmes disponíveis** compatíveis com essas características e exibe suas sinopses como recomendação.

---

## 🖥️ Interface

A interface gráfica foi desenvolvida utilizando **Tkinter**, oferecendo telas para:

- Tela inicial
- Catálogo de filmes
- Buscar filme
- Locar filme
- Devolver filme
- Cadastrar filme
- Remover filme
- Recomendação personalizada

A navegação ocorre por meio de botões que alteram dinamicamente o conteúdo da janela principal. 

---

## 📂 Estrutura do Projeto

```text
Locadora/
│
├── main.py
├── lib.py
├── filmes.csv
└── README.md
```

---

## 📊 Estrutura do Arquivo CSV

```text
titulo,classificacao,genero,sinopse,status
```

Exemplo:

```text
Toy Story,L,animacao,Brinquedos ganham vida.,disponivel
```

---

## 🎯 Objetivos

Este projeto foi desenvolvido com o objetivo de praticar:

- manipulação de arquivos CSV;
- desenvolvimento de interfaces gráficas;
- organização de funções em módulos;
- persistência de dados sem banco de dados;
- validação de entradas do usuário;
- lógica de programação.

---

## 📚 Conceitos Aplicados

- Manipulação de Arquivos
- Interface Gráfica com Tkinter
- Estruturas de Dados
- Leitura e Escrita em CSV
- Modularização do Código
- Tratamento de Strings
- Validação de Dados

---

## 📷 Demonstração

<img width="752" height="499" alt="locadora" src="https://github.com/user-attachments/assets/63e4b6a3-725d-4af9-904e-f714ed573c46" />

<img width="752" height="499" alt="Captura de tela 2026-02-22 135517" src="https://github.com/user-attachments/assets/b9d34af4-ed86-4798-97b9-5a1c22c3e2be" />

<img width="752" height="499" alt="Captura de tela 2026-02-22 135427" src="https://github.com/user-attachments/assets/ae270489-0259-46a9-b168-d27fdf603e6c" />

