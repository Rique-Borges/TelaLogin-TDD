# Projeto Tela de Login

Este projeto consiste em uma simples tela de login desenvolvida em Java, onde os usuários podem fazer login com um nome de usuário e senha, além de adicionar novos usuários ao banco de dados. O objetivo é criar uma interface gráfica que permita a autenticação e a gestão de usuários de forma eficiente e segura.

## Pré-requisitos

- **Linguagem:** Java
- **Bibliotecas:** JUnit para testes unitários, Swing para a interface gráfica
- **IDE:** Eclipse

## Estrutura do Projeto

### Classes

- **TelaDeLogin:** Esta classe representa a tela de login e possui métodos para realizar login e adicionar usuários ao banco de dados.
  - **Métodos:**
    - `public boolean login(String username, String password)`: Verifica as credenciais do usuário e realiza o login.
    - `public void adicionarUsuario(String username, String password)`: Adiciona um novo usuário ao banco de dados.

- **TelaLoginTeste:** Esta classe contém testes unitários para a classe `TelaDeLogin`, verificando se os métodos de login e adição de usuário funcionam corretamente.
  - **Métodos:**
    - `@Test public void testeLoginComSucesso()`: Testa um caso de sucesso no login.
    - `@Test public void testeLoginFalho()`: Testa um caso de falha no login.
    - `@Test public void testeAdicionarUsuario()`: Testa a adição de um novo usuário.

## Implantações

As funcionalidades de login e adição de usuários foram aplicadas dentro da atividade principal da tela de login, utilizando a biblioteca Swing para a interface gráfica. A classe `TelaDeLogin` centraliza a lógica do aplicativo, enquanto `TelaLoginTeste` garante a qualidade do código através de testes unitários.

## Versionamento

- **Versão 1.0:**
  - Implementação inicial da tela de login.
  - Adição da funcionalidade de login.
  - Adição da funcionalidade de adicionar novos usuários.
  - Inclusão de testes unitários básicos.

## Autor

- **Nome completo:** Henrique Ribeiro Borges
- **E-mail:** henriqueribeiroborges@gmail.com
- **RA:** 223997
