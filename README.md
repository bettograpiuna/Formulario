# Formulário de Inscrição "Bem-vindo(a) a Bordo!" 🚢

Este é um projeto simples de front-end que cria uma página com um formulário de inscrição, utilizando uma divertida temática náutica. 

O objetivo é demonstrar o uso de elementos básicos de formulário em HTML5 para coletar dados de um usuário.

## 📝 Descrição do Projeto

A página apresenta um formulário para que novos "tripulantes" possam se inscrever. Cada campo do formulário foi nomeado de acordo com a
temática de navegação para criar uma experiência mais imersiva e criativa.

O projeto é construído inteiramente com **HTML** e utiliza **CSS inline** para estilização básica, como centralização de texto e cores.

## ✨ Funcionalidades

O formulário inclui os seguintes campos:

* **Nome:** `input type="text"` - Campo para o nome do(a) tripulante.
* **E-mail:** `input type="email"` - Campo para o e-mail, chamado de "Rádio de Contato".
* **Senha:** `input type="password"` - Campo para a senha, chamada de "Código de Embarque".
* **País:** `select` - Um menu de seleção para o "Porto de Origem".
* **Mensagem:** `textarea` - Uma área de texto para o "Diário de Bordo".

Além dos campos, o formulário possui:

* **Validação Simples:** O atributo `required` é usado nos campos essenciais para garantir que não sejam enviados em branco.
* **Botão de Enviar:** Submete os dados do formulário.
* **Botão de Limpar:** Reseta todos os campos para seus valores iniciais.

## 🏛️ Estrutura do Código

O código está contido em um único arquivo HTML e é estruturado semanticamente da seguinte forma:

* `<header>`: Contém o título principal "Bem-vindo(a) a Bordo!" e uma breve instrução.
* `<main>`: Abriga o elemento `<form>`, que contém todos os campos de entrada (`input`, `select`, `textarea`) e os botões.
* `<footer>`: Exibe uma mensagem de agradecimento e informações de copyright.

A estilização é aplicada diretamente nas tags HTML através do atributo `style` para manter o projeto simples e autocontido.

## 🚀 Como Visualizar

Para ver o formulário em ação, você não precisa de nenhum servidor ou ferramenta complicada. Basta seguir os passos:

1.  Faça o download do arquivo `index.html` deste repositório.
2.  Ou acesse: https://bettograpiuna.github.io/Formulario/
3.  Abra o arquivo diretamente no seu navegador de internet preferido (Google Chrome, Mozilla Firefox, etc.).

E pronto! A página do formulário será exibida.

**Observação:** 
Este projeto é focado apenas no front-end (a parte visual).
A funcionalidade de envio (`action="/submit"`) requer um backend para receber e processar os dados, o qual não faz parte deste 
repositório.
