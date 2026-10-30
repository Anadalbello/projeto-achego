# Lumi — Assistente Virtual do Achego

<p align="center">
  <b>Uma experiência de comunicação inteligente, acessível e acolhedora.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/Evolution_API-25D366?style=flat&logo=whatsapp&logoColor=white" alt="Evolution API">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
</p>

---

## 📋 1. Sobre o Projeto

A **Lumi** é a assistente virtual com Inteligência Artificial integrada ao **Achego — Plataforma de Acompanhamento Psicológico com Assistente de IA**.

Seu propósito é facilitar a comunicação por meio do WhatsApp, oferecendo uma interação simples e acessível. A assistente utiliza Inteligência Artificial para interpretar mensagens e gerar respostas em linguagem natural.

---

## ✨ 2. Funcionalidades Principais

* **Atendimento Automatizado:** Recebimento e resposta de mensagens pelo WhatsApp.
* **Inteligência Artificial:** Processamento de mensagens e geração de respostas com Google Gemini.
* **Controle de Acesso:** Restrição de respostas a um número de WhatsApp autorizado.
* **Integração de Serviços:** Comunicação automatizada entre WhatsApp, Evolution API e n8n.

---

## 🛠️ 3. Tecnologias Utilizadas

* **Automação:** n8n
* **Inteligência Artificial:** Google Gemini
* **Integração com WhatsApp:** Evolution API
* **Canal de Comunicação:** WhatsApp
* **Infraestrutura:** Docker

---

## ⚙️ 4. Funcionamento

A Lumi utiliza um fluxo automatizado no n8n para realizar a comunicação entre os serviços:

1. O WhatsApp recebe uma mensagem do usuário.
2. A Evolution API encaminha o evento ao webhook do n8n.
3. O n8n verifica se o número remetente está autorizado.
4. O Google Gemini processa a mensagem e gera uma resposta.
5. A Evolution API envia a resposta ao WhatsApp.

O fluxo possui uma validação de acesso que permite o processamento somente de mensagens provenientes do número autorizado.