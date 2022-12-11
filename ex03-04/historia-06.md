## História 06

### Gerenciar Pessoas

> - Como administrador(a),
> - Eu desejo gerenciar pessoas no sistema,
> - Para que eu tenha um controle maior de fluxo do meu estabelecimento.

### Critérios de Aceitação
- Cenário 1: Selecionar tipo de pessoa
  - Dado: que eu esteja na página de cadastro de pessoas;
  - Quando: eu selecionar o tipo de pessoa;
  - Então: eu devo selecionar uma opção entre "cliente" e "funcionário".

- Cenário 2: Dados incompletos
  - Dado: que eu envie o formulário de cadastro de uma pessoa;
  - Quando: não for preenchido o nome ou CPF da pessoa;
  - Então: o sistema deve me retornar um erro de dados incompletos.

- Cenário 3: pessoa já existente
  - Dado: que eu envie o cadastro de uma pessoa;
  - Quando: essa pessoa já existir no sistema;
  - Então: o sistema deve me retornar uma informação de que essa pessoa já existe.