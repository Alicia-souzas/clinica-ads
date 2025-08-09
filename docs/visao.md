# Documento de Requisitos – Sistema de Agendamento Médico

## 1. Objetivo

Proporcionar **facilidade e agilidade** no agendamento e remarcação de consultas, com foco em **organização de datas e horários**, tanto diários quanto semanais.

## 2. Escopo

### Escopo **Incluído (IN)**

- Cadastro de usuários (médicos e funcionários)  
- Definição da disponibilidade de cada médico  
- Cadastro de pacientes  
- Agendamento e cancelamento de consultas  
- Exibição de mensagens de erro claras e objetivas  

### Escopo **Excluído (OUT)**

- Agendamento feito pelos pacientes em casa  
- Envio de mensagens diretas para médicos  
- Funcionalidades de faturamento e convênios  
- Relatórios e dashboards avançados  

## 3. Regras de Negócio (RB)

- Horários (slots) de consulta **não podem se sobrepor** a outros agendamentos  
- Consultas **devem ocorrer dentro da janela de atendimento** do profissional  
- Cancelamentos **devem liberar imediatamente o horário** (slot) para novo agendamento  
- A duração padrão de uma consulta é de **30 minutos** (configurável por profissional)  

## 4. Premissas

- Horário de funcionamento: das **08h00 às 10h00**  
- MVP limitado a **uma clínica** com até **10 profissionais**  
- Base inicial com até **500 pacientes cadastrados**  

## 5. Stakeholders

- Atendentes  
- Médicos  
- Pacientes  
- Gestor da clínica  
