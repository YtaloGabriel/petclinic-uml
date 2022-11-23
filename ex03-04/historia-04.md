## História 04

### Gerenciar Agendas

> - Como funcionário
> - Eu desejo gerenciar agendas
> - Para que eu tenha um controle das consultas marcadas

### Critérios de Aceitação
- Cenário 1: Adicionar Agenda
  - Dado: que eu esteja na página de agendas;
  - Quando: eu selecionar a opção de criar agendas;
  - Então: o sistema deve me mostrar as entradas/inputs para criar uma nova agenda.

- Cenário 2: Deletar Agenda
  - Dado: que eu esteja numa agenda específica;
  - Quando: eu selecionar a opção de deletar agenda;
  - Então: o sistema deve remover a agenda selecionada;
    - E: o sistema deve me mostrar uma mensagem de agenda removida.

- Cenário 3: Editar Agenda
  - Dado: que eu esteja numa agenda específica;
  - Quando: eu selecionar a opção de editar agenda;
  - Então: o sistema deve me mostrar as entradas/inputs para editar a agenda selecionada;