## História 03

### Gerenciar Atendimentos

> - Como funcionário
> - Eu desejo gerenciar os atendimentos disponíveis na petclinic 
> - Para que os agendamentos sempre estejam de acordo com os serviços que podem ser ofertados.

### Critérios de Aceitação
- Cenário 1: Atendimentos iguais
  - Dado: que eu esteja na página de atendimentos;
  - Quando: eu tentar criar um atendimento;
    - E: o tipo de atendimento já estiver cadastrado;
  - Então: o sistema não permitirá que eu crie esse atendimento;
    - E: eu devo receber uma mensagem de atendimento já existente.

- Cenário 2: Atendimento sem tempo médio
  - Dado: que eu esteja na página de atendimentos;
  - Quando: eu enviar um novo tipo atendimento;
    - E: eu não informar o tempo médio para realização de cada atendimento;
  - Então: o sistema não permitirá que os dados sejam enviados;
    - E: eu devo receber uma mensagem informando que o campo de tempo médio é obrigatório.

- Cenário 3: Atendimento não vinculado com um profissional
  - Dado: que eu esteja criando um atendimento;
  - Quando: eu enviar um atendimento novo ou editado;
    - E: o atendimento não conter o campo de profissional responsável;
  - Então: eu devo receber uma mensagem de erro do sistema, informando que o campo de profissional é obrigatório.