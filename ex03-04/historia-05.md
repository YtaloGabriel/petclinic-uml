## História 05

### Realizar Login

> - Como funcionário
> - Eu desejo realizar um login na plataforma
> - Para que eu tenha acesso a informações restritas de maneira mais segura

### Critérios de Aceitação
- Cenário 1: Informações Corretas
  - Dado: que eu envie o formulário de login;
  - Quando: as minhas credenciais existirem no sistema;
  - Então: eu devo ser levado para uma tela de funcionário logado.

- Cenário 2: Senha Incorreta
  - Dado: que eu envie o formulário de login;
  - Quando: meu nome existir no sitema;
    - E: a minha senha não estiver igual a cadastrada;
  - Então: Eu devo receber uma mensagem de senha incorreta.

- Cenário 3: Funcionário Inexistente
  - Dado: que eu envie o formulário de login;
  - Quando: não existir nenhum funcionário com as informações enviadas;
  - Então: eu devo receber uma mensagem de usuário inexistente.