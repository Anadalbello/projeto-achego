# Requisitos do Sistema — Achego

## 1. Objetivo

Definir os requisitos funcionais, requisitos não funcionais e regras de negócio da plataforma Achego.

## 2. Atores

- **Paciente:** consulta os próprios atendimentos e utiliza as funcionalidades disponíveis para seu perfil.
- **Psicólogo:** gerencia as funcionalidades de atendimento autorizadas para seu perfil.
- **Administrador:** perfil opcional, a confirmar durante a definição do escopo.

## 3. Requisitos funcionais

| ID | Descrição | Prioridade |
|---|---|---|
| RF01 | O sistema deve permitir que o usuário realize login. | Alta |
| RF02 | O sistema deve permitir que o paciente consulte seus agendamentos. | Alta |
| RF03 | O sistema deve permitir que o psicólogo consulte sua agenda. | Alta |
| RF04 | O sistema deve permitir o cadastro de pacientes autorizados. | Alta |
| RF05 | O sistema deve permitir o cadastro de psicólogos. | Alta |
| RF06 | O sistema deve permitir a solicitação de um agendamento. | Alta |
| RF07 | O sistema deve permitir a consulta das informações do atendimento pelo usuário autorizado. | Alta |
| RF08 | O sistema deve permitir a atualização dos dados de perfil autorizados. | Média |
| RF09 | O sistema deve disponibilizar um canal para solicitação de suporte. | Média |
| RF10 | O sistema deve permitir que o usuário interaja com a Lumi para obter orientação sobre a utilização da plataforma. | Média |

## 4. Requisitos não funcionais

| ID | Descrição | Prioridade |
|---|---|---|
| RNF01 | O sistema deve exigir autenticação para acessar funcionalidades privadas. | Alta |
| RNF02 | O sistema deve controlar o acesso conforme o perfil e as permissões do usuário. | Alta |
| RNF03 | A interface deve apresentar textos e navegação claros para facilitar a utilização. | Média |
| RNF04 | O sistema deve validar os dados recebidos antes de processá-los. | Alta |
| RNF05 | O projeto deve manter documentação técnica que permita compreender e manter suas funcionalidades. | Média |

## 5. Regras de negócio

| ID | Regra |
|---|---|
| RN01 | O paciente só pode consultar os próprios agendamentos. |
| RN02 | O psicólogo só pode acessar informações de pacientes dentro das permissões estabelecidas para seu perfil e vínculo de atendimento. |
| RN03 | Um agendamento só pode ser confirmado se houver disponibilidade no horário solicitado. |
| RN04 | A solicitação de agendamento não deve ser apresentada como confirmação automática do atendimento. |
| RN05 | A Lumi não deve realizar diagnósticos nem substituir orientações do profissional de psicologia. |

## 6. Pontos pendentes de validação

- Definir se haverá cadastro público ou cadastro realizado por um perfil autorizado.
- Definir como o paciente solicitará, confirmará ou cancelará um atendimento.
- Definir quais informações estarão disponíveis para cada perfil.
- Definir os limites de atuação da Lumi e as situações em que deverá encaminhar o usuário para atendimento humano.
