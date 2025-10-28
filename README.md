# 📚 Sistema de Biblioteca com Tkinter

## 📝 Descrição

Este projeto é um **sistema de biblioteca com interface gráfica (GUI)** desenvolvido em **Python** utilizando **Tkinter**.
O sistema permite **cadastrar usuários, realizar login e gerenciar livros** associados a cada usuário individualmente.

---

## ⚙️ Funcionalidades

### 👤 **Gerenciamento de Usuários**

* Cadastro de novos usuários com **matrícula, nome e senha**.
* Verificação automática para evitar **cadastros duplicados**.
* Login com **validação de credenciais**.

### 📖 **Controle de Livros**

* Cada usuário pode **visualizar seus próprios livros**.
* Adicionar novos livros informando:

  * Nome do livro
  * Autor
  * Código do livro
* Os dados são salvos em **arquivos de texto locais**, sem necessidade de banco de dados.

### 💻 **Interface Gráfica (Tkinter)**

O sistema conta com uma interface simples e intuitiva:

1. **Tela Inicial:** opções de *Cadastro* e *Login*
2. **Tela de Cadastro:** formulário para criar um novo usuário
3. **Tela de Login:** validação de credenciais
4. **Tela do Usuário:** exibe os livros cadastrados e permite adicionar novos

---

## 🗂️ Estrutura dos Arquivos

* `usuarios.txt` → Armazena os usuários cadastrados

  ```
  matricula,nome,senha
  ```
* `livros.txt` → Armazena os livros cadastrados por usuário

  ```
  matricula,nome_do_livro,autor,codigo
  ```

---

## 🧠 Principais Funções

| Função                   | Descrição                                         |
| ------------------------ | ------------------------------------------------- |
| `inicializar_arquivos()` | Cria os arquivos necessários, caso não existam.   |
| `cadastrar_usuario()`    | Cadastra um novo usuário, verificando duplicatas. |
| `validar_login()`        | Valida matrícula e senha do usuário.              |
| `obter_livros()`         | Retorna os livros cadastrados de um usuário.      |
| `adicionar_livro()`      | Adiciona um novo livro vinculado a um usuário.    |

---

## 🚀 Como Executar

1. Certifique-se de ter o **Python 3** instalado.
2. Baixe ou clone este repositório:

   ```bash
   git clone https://github.com/seuusuario/sistema-biblioteca.git
   ```
3. Execute o arquivo principal:

   ```bash
   python biblioteca.py
   ```

---

## 🧩 Tecnologias Utilizadas

* **Python 3**
* **Tkinter** (interface gráfica)
* **Arquivos `.txt`** (armazenamento de dados)

---

## 🧔 Autor

Desenvolvido por **Luiz Henrique Lima da Silva** 
💡 Projeto simples de estudo e prática com **Tkinter** e **manipulação de arquivos**.

---
