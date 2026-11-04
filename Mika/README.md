# Mika

<p align="center">
  <b>Uma assistente inteligente para simplificar a gestão de consultas e a rotina profissional.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Evolution_API-25D366?style=flat&logo=whatsapp&logoColor=white" alt="Evolution API">
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis">
</p>

---

## 📋 1. Sobre o Projeto

A **Mika** é uma assistente virtual desenvolvida para auxiliar uma psicóloga na organização de consultas e tarefas administrativas por meio do WhatsApp.

O projeto utiliza inteligência artificial e automações para integrar ferramentas como Google Calendar e Google Drive, facilitando o gerenciamento da agenda e a organização de documentos profissionais.

A solução faz parte do ecossistema **Achego** e tem como objetivo explorar a aplicação da inteligência artificial na otimização de processos administrativos da área de psicologia.

---

## ✨ 2. Funcionalidades Principais

- **Assistente via WhatsApp:** Recebimento e interpretação de solicitações enviadas pela psicóloga.
- **Gestão de Agenda:** Consulta de disponibilidade e organização de compromissos no Google Calendar.
- **Organização de Prontuários:** Localização e criação de pastas de pacientes no Google Drive.
- **Documentação de Atendimentos:** Criação e organização de documentos no Google Docs.
- **Memória de Conversação:** Utilização do PostgreSQL para manter o contexto das interações.
- **Controle de Acesso:** Restrição do processamento de mensagens ao número autorizado, com filtros para mensagens de grupos e mensagens enviadas pela própria instância.

---

## 🛠️ 3. Tecnologias Utilizadas

O ecossistema técnico do projeto abrange as seguintes tecnologias e ferramentas:

- **Automação de Processos:** n8n
- **Integração com WhatsApp:** Evolution API
- **Inteligência Artificial:** Google Gemini
- **Banco de Dados:** PostgreSQL
- **Gerenciamento de Cache e Filas:** Redis
- **Containerização:** Docker e Docker Compose
- **Integrações Google:** Google Calendar API e Google Drive API
- **Controle de Versão:** Git e GitHub

---

## ⚙️ 4. Arquitetura e Funcionamento

A Mika utiliza uma arquitetura baseada em serviços integrados por meio de containers Docker.

O fluxo de funcionamento ocorre da seguinte forma:

1. A psicóloga envia uma solicitação pelo WhatsApp.
2. A Evolution API recebe a mensagem e encaminha o evento ao n8n.
3. O n8n verifica as condições de acesso e processa a solicitação.
4. O Google Gemini interpreta a mensagem e identifica a tarefa solicitada.
5. Quando necessário, a automação utiliza as integrações com Google Calendar e Google Drive.
6. A resposta é encaminhada à psicóloga pelo WhatsApp.

---

## 📁 5. Estrutura do Projeto

```text
mika/
├── README.md
├── .gitignore
├── .env.example
├── docker-compose.yml
├── workflows/
│   └── mika-workflow.json
└── docs/
```