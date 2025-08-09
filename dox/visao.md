
1 Objetivo do agendamento online: facilitar o andamento e o atendimento da clinica evitando filas presencialmente  

2 escopo: IN - dentro do escopo
cadastro de usuarios
disponibilidade de cada medico
cadastro de pacientes 
agendar e cancelar consultas 
exibir mensagem de erro caso ocorra choque de horarios 

3 escopo: OUT - fora do escopo
agendamento em casa
nao havera envios de mensagens de horarios para os medicos 
prontuario eletronico
não funcionara para mais de uma clinica 
faturamento e convenios

4 regras de negocios RB
consultas so podem ocorrer dentro da janela de atendimento do profissional
slot de horarios nao pode se sobrepor a outro ja ocupado
a duracao padrao de consulta e de 30 minutos 
cancelamento deve liberar o slot imediatamente 

5 premissas:
horario comercial base: 08h as 18h
Mvp limitado a uma clinica ate 10 profissionais 

6 stakeholders: 
atendentes
medicos
pacientes
gestor da clinica 



# 📄 Documento de Visão – Sistema de Agendamento Online para Clínica

## 1. 🎯 Objetivo

Facilitar o processo de agendamento e atendimento na clínica, reduzindo filas presenciais e otimizando o fluxo de pacientes e profissionais de saúde.

---

## 2. 📌 Escopo

### 2.1 Dentro do Escopo (IN)

- Cadastro de usuários (pacientes, atendentes, médicos)
- Visualização da disponibilidade de cada médico
- Cadastro de pacientes
- Agendamento e cancelamento de consultas
- Exibição de mensagens de erro em caso de conflitos de horário

### 2.2 Fora do Escopo (OUT)

- Agendamento de consultas domiciliares
- Envio automático de notificações de agendamento para médicos
- Integração com prontuário eletrônico
- Suporte para múltiplas clínicas
- Faturamento e integração com convênios

---

## 3. 📐 Regras de Negócio (RB)

- Consultas só podem ser agendadas dentro da janela de atendimento do profissional
- Horários de consulta não podem se sobrepor a horários já agendados
- Duração padrão de cada consulta: **30 minutos**
- Cancelamentos devem liberar imediatamente o horário anteriormente reservado

---

## 4. ✅ Premissas

- Horário comercial da clínica: **08h às 18h**
- MVP será limitado a **uma única clínica** com até **10 profissionais de saúde**

---

## 5. 👥 Stakeholders

- Atendentes
- Médicos
- Pacientes
- Gestor da clínica
