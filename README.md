# Projeto-Agenda
Ideia de projeto - sistema de agendamento e cancelamento de pacientes

A ideia é construir algo simples, funcional e que atenda às necessidades de um profissional que trabalhe com atendimentos, datas e horarios marcados, como um fisioterapeuta, por exemplo

. Abaixo, mostrarei um passo a passo da ideá para criação do projeto até agora:

🧠 Objetivo do sistema

Criar um sistema onde o profissional consiga:

Ver todos os pacientes agendados para o dia;

Marcar quem confirmou ou cancelou;

Ver a contagem total de atendimentos confirmados e cancelados.

💻 Ferramentas que pretendo utilizar:

Começar com Python + SQLite (banco de dados leve) ou até mesmo um sistema com interface gráfica simples (Tkinter).

📌 Estrutura Básica da Solução

🗃️ Banco de Dados: Tabela *Agendamentos*

| Campo          | Tipo    | Exemplo                               |
| -------------- | ------- | ------------------------------------- |
| id             | INTEGER | 1                                     |
| nome\_paciente | TEXT    | "João Silva"                          |
| data           | DATE    | "2025-08-26"                          |
| horario        | TEXT    | "14:30"                               |
| status         | TEXT    | "Confirmado", "Cancelado", "Pendente" |



🧱 Funcionalidades

Adicionar novo agendamento

Ver lista de agendamentos do dia

Alterar status do agendamento (confirmado/cancelado)

Contar total de agendamentos por status

OBS : Futuramente, pretendo transformar em mobile, um app onde haja interação entre paciente e fisioterapeuta, onde o próprio paciente possa confirmar seu agendmento prévio no aplicativo.
