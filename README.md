<h1 align="center">🧾 P2MBrasil Content Generator</h1>

<p align="center">
Gerador de código BBCode para criação de posts completos em fóruns (Categoria: Filmes).
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Legacy-lightgrey">
  <img src="https://img.shields.io/badge/Linguagem-PHP-blue">
  <img src="https://img.shields.io/badge/Tipo-Utility-lightgrey">
</p>

---

## 📌 Sobre

O **P2MBrasil Content Generator** é uma aplicação desenvolvida em PHP para automatizar a criação de posts completos em fóruns, com foco na categoria **Filmes**.

O sistema foi projetado para o ambiente do **P2MBRASIL.COM**, onde era necessário padronizar publicações utilizando **BBCode com suporte a HTML ([dohtml])**.

A ferramenta elimina a necessidade de montagem manual de posts, gerando automaticamente um layout estruturado e pronto para uso.

---

## ⚙️ Como funciona

O sistema é dividido em duas etapas principais:

### 🧩 1. Entrada de dados (Formulário)

O usuário preenche um formulário com todas as informações do conteúdo:

- Título, gênero, duração e ano  
- Elenco e sinopse  
- Informações técnicas (resolução, codecs, formato, etc.)  
- Poster e imagens (screenshots)  
- Comentários do uploader  
- Dados de download (contas, login e senha)  

O próprio sistema orienta o usuário a:

> "Preencher todos os campos corretamente e gerar o código para copiar e colar no fórum."

---

### ⚙️ 2. Processamento

- Validação automática dos campos  
- Tratamento de valores vazios com padrões (ex: "N/A", "Indisponível")  
- Sanitização de dados (`htmlspecialchars`, `stripslashes`)  
- Organização das informações para montagem do layout  

---

### 🧾 3. Geração do código

Ao final, o sistema gera um bloco completo em:

- **BBCode estruturado**
- **HTML embutido ([dohtml])**
- Layout com tabelas, imagens e formatação visual

O resultado é exibido em um `<textarea>` pronto para:

👉 **CTRL + C → CTRL + V diretamente no fórum**

---

## 🧠 Funcionalidades

- Geração automática de layout completo para posts  
- Estrutura visual com tabelas (capa, cenas, ficha técnica)  
- Tratamento automático de campos vazios  
- Suporte a múltiplas imagens (poster + screenshots)  
- Geração de sinopse, elenco e comentários  
- Inclusão de dados técnicos detalhados  
- Sistema de múltiplos downloads por CD  

---

## 🔗 Estrutura de Downloads

O sistema suporta múltiplas fontes de download, organizadas automaticamente:

### Peer2Mail (P2M)
- Contas múltiplas por CD  
- Login e senha organizados  

### Ilusions Downloader (ID)
- Estrutura independente de contas  

### Iddeias (IDS)
- Suporte adicional com separação por CD  

Cada fonte é organizada em blocos separados, facilitando a leitura no fórum.

---

## 🎯 Quando usar

- Criação de posts completos em fóruns  
- Padronização de uploads de filmes  
- Organização de conteúdo com múltiplas partes  
- Redução de erros manuais em BBCode  

---

## 🏛️ Contexto

Este projeto representa uma fase da web onde fóruns utilizavam intensivamente **BBCode avançado com HTML embutido**, exigindo alto nível de organização manual para criação de conteúdo.

A ferramenta foi desenvolvida para automatizar esse processo, trazendo:

- Padronização  
- Produtividade  
- Melhor experiência visual  

---

## 🙏 Créditos

<p align="center">
Gerador desenvolvido por <b>Phobos</b><br><br>
Em memória de <b>Gustavo Aroeira Tiso de Melo, falecido em 23/04/2012</b><br>
Contribuição e parceria fundamentais para este projeto.
</p>
