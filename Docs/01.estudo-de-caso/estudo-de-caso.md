# Estudo de Caso — Achego

## 1. Identificação do projeto

**Nome:** Achego

**Título:** Plataforma de Acompanhamento Psicológico com Assistente Virtual Lumi.


## 2. Contextualização

O Achego é uma proposta de plataforma digital voltada ao acompanhamento psicológico, com o objetivo de facilitar a organização dos atendimentos e a interação entre pacientes e profissionais de psicologia.

A proposta reúne funcionalidades de consulta de agendamentos, acesso autorizado às informações da plataforma e solicitação de suporte. Também prevê a integração de uma assistente virtual chamada Lumi, destinada a auxiliar os usuários na navegação pelo sistema.

## 3. Problema identificado

A proposta busca atender à necessidade de centralizar funcionalidades relacionadas à organização dos atendimentos psicológicos e facilitar o acesso dos usuários às informações disponibilizadas pela plataforma.

## 4. Justificativa

O desenvolvimento do Achego permitirá aplicar conhecimentos de análise e modelagem de sistemas, banco de dados, desenvolvimento web, APIs e automação.

O projeto busca explorar como uma plataforma digital pode facilitar a organização dos atendimentos e a utilização de funcionalidades de apoio, respeitando os limites de atuação de uma ferramenta tecnológica na área da psicologia.

## 5. Objetivo geral

Desenvolver uma plataforma digital para apoiar a organização e o acompanhamento dos atendimentos psicológicos, com funcionalidades voltadas a pacientes e profissionais de psicologia.

## 6. Objetivos específicos

- Identificar e documentar os requisitos do sistema.
- Modelar os processos e a estrutura de dados da plataforma.
- Desenvolver uma API para disponibilizar as funcionalidades do sistema.
- Construir uma interface para interação dos usuários.
- Integrar a assistente virtual Lumi por meio de fluxos de automação no n8n.
- Realizar testes para verificar o funcionamento das funcionalidades desenvolvidas.
- Documentar as decisões técnicas e as etapas de desenvolvimento.

## 7. Público-alvo

**Pacientes:** usuários que precisam consultar os próprios agendamentos e acessar as funcionalidades disponibilizadas para seu perfil.

**Profissionais de psicologia:** usuários que precisam consultar e organizar informações relacionadas aos atendimentos autorizados.

## 8. Solução proposta

A solução consiste em uma plataforma web com funcionalidades de organização de atendimentos e acesso controlado às informações.

O backend será desenvolvido com Java e Spring Boot, utilizando PostgreSQL para armazenamento de dados. A interface será construída com React e TypeScript.

A assistente virtual Lumi será integrada por meio do n8n e de uma API de inteligência artificial. Sua função será auxiliar na navegação e na utilização das funcionalidades disponíveis, sem substituir o profissional de psicologia ou realizar diagnósticos.

## 9. Escopo inicial

A primeira versão deverá priorizar:

- Autenticação e controle de acesso.
- Consulta e organização de agendamentos.
- Acesso às informações permitidas para cada perfil.
- Solicitação de suporte.
- Integração inicial da Lumi para orientação sobre o uso da plataforma.

Os detalhes e as prioridades serão refinados durante o levantamento de requisitos.

## 10. Limitações e cuidados

A plataforma deverá respeitar as permissões de acesso e a privacidade das informações. Os testes deverão utilizar dados fictícios, sem exposição de informações pessoais ou clínicas reais.

A Lumi não deverá realizar diagnósticos, prescrever tratamentos ou se apresentar como serviço de emergência.

## 11. Tecnologias planejadas

- Java
- Spring Boot
- PostgreSQL
- React
- TypeScript
- n8n
- API de inteligência artificial
- Git e GitHub

As tecnologias poderão ser ajustadas conforme a evolução do projeto e as necessidades identificadas.