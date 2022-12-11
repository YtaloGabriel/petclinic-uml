## História 02

### Monitoramento de Agenda

> - Como funcionário
> - eu desejo visualizar todas as agendas disponíveis
> - para saber quais horários estão disponíveis para novas marcações

### Critérios de Aceitação
- Cenário 1: Visualização por período
  - Dado: que eu esteja na página de Agendas;
  - Quando: eu selecionar uma opção dos períodos;
  - Então: O sistema deverá me mostrar as agendas separadas por dia, semana ou mês.

- Cenário 2: Visualização por período
  - Dado: que eu esteja na página de agendas;
  - Quando: eu selecionar um período específico;
  - Então: o sistema deverá me mostrar cada agendamento do respectivo período;
    - E: deve ser informado a data, a hora e o nome do cliente.
  
- Cenário 3: Destaque de consultas remarcadas
  - Dado: que eu esteja na página de agendas;
  - Quando: eu selecionar a opção de consultas remarcadas;
  - Então: o sistema deverá me mostrar uma lista apenas com as consultas que já foram remarcadas pelo menos uma vez.