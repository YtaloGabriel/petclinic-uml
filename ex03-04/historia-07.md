## História 07

### Segurança: Páginas com autenticação

> - Como sistema
> - Eu desejo que todas as páginas, exceto a inicial, necessitem de autenticação/login de acesso
> - Para que todos os dados tenham uma camada a mais de proteção, a fim de evitar invasões.

### Critérios de Aceitação
- Cenário 1: Acesso negado a uma página protegida
  - Dado: que uma pessoa tente acessar uma rota protegida;
  - Quando: essa pessoa não não estiver autenticada/logada;
  - Então: o sistema não permitirá o login e deve encaminhar para a página de login.

- Cenário 1: Login com tempo de inatividade
  - Dado: que uma pessoa autenticada esteja querendo acessar uma rota;
  - Quando: essa pessoa estiver sem entrar na plataforma por mais de 7 dias;
  - Então: o login deverá ser bloqueado e solicitado um novo login.

- Cenário 1: Acessando a página inicial
  - Dado: que uma pessoa acesse a rota inicial;
  - Quando: essa pessoa estiver autenticada ou não;
  - Então: a pessoa poderá ter livre acesso a página.