## História 01

### Gerenciar Clientes

> - Como dono do petclinic
> - Eu desejo gerenciar (CRUD) todos os clientes 
> - Para que eu tenha um controle total dos clientes presentes na minha plataforma.

### Critérios de Aceitação

- Cenário 1: Pesquisar por cliente
  - Dado: que eu esteja realizando uma busca de clientes;
  - Quando eu enviar as informações do cliente;
    - E: O cliente não estiver cadastrado no sistema
  - Então: O sistema deverá informar uma mensagem de cliente não existente.
  
- Cenário 2: Adicionando um novo cliente
  - Dado: que eu envie os dados de um novo cliente;
  - Quando: O CPF do cliente já pertencer a um outro cliente cadastrado;
  - Então: O sistema deverá informar que já existe um cliente cadastrado com esse CPF.

- Cenário 3: Cliente sem dados importantes
  - Dado: que eu esteja adicionando um novo cliente;
  - Quando: o CPF do cliente não for informado;
    - E: O nome do cliente não for informado;
  - Então: O sistema não permitirá que o cliente seja criado;
    - E: O sistema deverá informar que CPF e Nome são campos obrigatórios.
