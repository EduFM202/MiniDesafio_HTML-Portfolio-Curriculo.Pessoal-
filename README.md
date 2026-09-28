# 💼 Mini Desafio HTML — Portfólio & Currículo Pessoal

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Página de **Portfólio / Currículo Web** desenvolvida como atividade prática para a disciplina. O objetivo principal do projeto é demonstrar o domínio de **HTML5 semântico**, organizando informações pessoais, lista de habilidades, histórico de projetos e um formulário de contato completo.

---

## 🎯 Objetivo

Criar uma página HTML limpa, estruturada de forma semântica e funcional, reproduzindo fielmente os tópicos e a organização solicitados no modelo do desafio.

---

## 📋 Requisitos Implementados

- [x] **Cabeçalho & Navegação (`<header>`, `<nav>`):** Título principal com nome/cargo e menu com links internos (âncoras `#sobre`, `#projetos`, `#contato`).
- [x] **Seção "Sobre Mim" (`<section id="sobre">`):** 
  - Foto de perfil configurada exatamente nas dimensões `150x150px` (`width="150"` e `height="150"`).
  - Texto de apresentação e lista de habilidades.
- [x] **Seção "Meus Projetos" (`<section id="projetos">`):**
  - Tabela estruturada com `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` e `<td>`.
  - 4 colunas: *Projeto*, *Tecnologias*, *Status* e *Link* (com hiperlinks funcionais).
- [x] **Seção "Entre em Contato" (`<section id="contato">`):**
  - Formulário envolto pela tag `<fieldset>` e identificação `<legend>` ("Dados do Contato").
  - Campos de entrada: *Nome*, *E-mail*, menu suspenso `<select>` para *Assunto* e `<textarea>` para *Mensagem*.
  - Todos os campos devidamente vinculados aos seus respectivos `<label>`.
  - Botão de envio (`<button type="submit">`).
- [x] **Rodapé (`<footer>`):**
  - Declaração de direitos autorais utilizando o caractere especial HTML `&copy;`.
  - E-mail e telefone para contato.

---

## 📁 Estrutura do Repositório

```text
├── index.html      # Estrutura principal do Portfólio/Currículo em HTML5
├── eu.png          # Imagem de perfil (150x150px)
└── README.md       # Documentação do desafio
