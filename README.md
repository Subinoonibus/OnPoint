# OnPoint - Sistema de Gerenciamento de Consultórios

**OnPoint** é um sistema de gerenciamento de agendas voltado para consultórios.  
O objetivo do projeto é facilitar a organização de consultas, otimizar o tempo dos profissionais de saúde e melhorar a experiência dos pacientes.

---

## 💡 Solução Proposta
A aplicação oferecerá:

- Cadastro de pacientes e profissionais
- Agendamento e cancelamento de consultas
- Visualização de agenda diária, semanal e mensal
- Notificações de lembrete
- Relatórios de atendimento

---

## 🚀 Status do Projeto
📌 Em desenvolvimento – tecnologias e arquitetura ainda em definição.  

---

## 📌 Backlog do Produto

| Rank | Prioridade | User Story | Estimativa (Story Points) | Sprint Prevista | Critério de Aceitação | Status |
|------|------------|------------|----------------------------|-----------------|------------------------|--------|
| 1 | Alta | Como **secretária**, quero **cadastrar pacientes** para que eu possa manter seus dados organizados. | 5 | Sprint 1 | O sistema deve permitir cadastrar, editar e visualizar informações básicas (nome, telefone, e-mail, CPF). | Em progresso |
| 2 | Alta | Como **paciente**, quero **agendar uma consulta** para que eu tenha um horário reservado. | 8 | Sprint 1 | O sistema deve permitir selecionar data, horário e profissional disponível. | Em progresso |
| 3 | Média | Como **profissional de saúde**, quero **visualizar minha agenda diária** para que eu saiba meus atendimentos. | 5 | Sprint 2 | A agenda deve mostrar horário, nome do paciente e status da consulta. | Não iniciado |
| 4 | Média | Como **paciente**, quero **cancelar consultas** para liberar horários. | 3 | Sprint 2 | Deve ser possível cancelar até 24h antes, com atualização automática da agenda. | Não iniciado |
| 5 | Baixa | Como **gestor do consultório**, quero **gerar relatórios de atendimentos** para analisar a produtividade. | 8 | Sprint 3 | Relatório deve incluir número de consultas por período, taxa de cancelamento e pacientes atendidos. | Não iniciado |
| 6 | Baixa | Como **paciente**, quero **receber notificações de lembrete** para não esquecer minhas consultas. | 13 | Sprint 3 | Sistema deve enviar e-mail ou SMS 24h antes da consulta. | Não iniciado |

---

## 🚧 **Sprints do Projeto OnPoint**

### **Sprint 1 - Início e Funcionalidades Básicas**
  
**Objetivo principal**: Implementar o cadastro de pacientes e o agendamento de consultas, garantindo que o fluxo básico de usuários seja atendido.

#### **Tarefas da Sprint 1**:
1. **Cadastro de pacientes**  
   - Funcionalidade de cadastro, edição e visualização de informações básicas (nome, telefone, e-mail, CPF).  
   - **Status**: Em progresso

2. **Agendamento de consultas**  
   - Permitir que o paciente agende consultas, com a seleção de data, horário e profissional disponível.  
   - **Status**: Em progresso

#### **Critérios de Aceitação**:
- Cadastro de pacientes deve ser funcional.
- Sistema de agendamento de consultas deve permitir escolher data e profissional.

---

### **Sprint 2 - Funcionalidades de Visualização e Cancelamento**
  
**Objetivo principal**: Implementar a visualização de agenda dos profissionais e a funcionalidade de cancelamento de consultas pelos pacientes.

#### **Tarefas da Sprint 2**:
1. **Visualização da agenda diária**  
   - Permitir que o profissional de saúde visualize sua agenda do dia, incluindo horário, paciente e status da consulta.  
   - **Status**: Não iniciado

2. **Cancelamento de consultas**  
   - Permitir que o paciente cancele consultas até 24h antes do horário agendado, com atualização automática na agenda.  
   - **Status**: Não iniciado

#### **Critérios de Aceitação**:
- Profissional deve conseguir visualizar sua agenda diária com as informações relevantes.
- Paciente deve ser capaz de cancelar uma consulta com sucesso dentro do prazo permitido.

---

### **Sprint 3 - Relatórios e Notificações**
 
**Objetivo principal**: Desenvolver funcionalidades de relatórios de atendimentos e notificações de lembrete para pacientes.

#### **Tarefas da Sprint 3**:
1. **Geração de relatórios de atendimentos**  
   - Permitir que o gestor gere relatórios de produtividade, incluindo número de consultas, taxa de cancelamento e pacientes atendidos.  
   - **Status**: Não iniciado

2. **Notificações de lembrete para pacientes**  
   - Enviar e-mail ou SMS 24h antes da consulta, lembrando o paciente sobre o agendamento.  
   - **Status**: Não iniciado

#### **Critérios de Aceitação**:
- Relatórios devem ser gerados com base nos dados de atendimento.
- Sistema deve enviar notificações automáticas de lembrete para os pacientes.

---

### **Sprint 4 - Refinamento e Testes Finais**
 
**Objetivo principal**: Realizar testes finais, corrigir erros e garantir que a plataforma esteja pronta para o lançamento.

#### **Tarefas da Sprint 4**:
- Testes de integração e performance.
- Refinamento de funcionalidades.
- Correção de bugs identificados nas sprints anteriores.

#### **Critérios de Aceitação**:
- Sistema sem erros críticos.
- Funcionalidades testadas e funcionando conforme esperado.

---

## 📄 Tecnologias Utilizadas

- Figma
- JavaScript
- Html
