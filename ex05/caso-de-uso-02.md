## Caso de Uso 02

### Cadastrar Funcionários
#### Ator: Administrador

#### Fluxo Normal:
1. Autenticar administrador
2. administrador informa o nome do funcionário
3. administrador informa o CPF do funcionário
4. administrador efetua o cadastro do funcionário

#### Extensões:
- 1.1. Se o administrador não estiver autenticado, solicitar um logn válido.
- 2.1. Se o administrador não informar nenhum nome de funcionário, solicitar um nome válido.
- 3.1. Se o administrador não informar CPF do funcionário, informar que o campo de CPF é obrigatório.
- 3.2. Se o CPF não estiver completo/válido, pedir para que o administrador informe um CPF válido.
- 3.3. Se o CPF já estiver cadastrado no sistema, informar que o funcionário já existe.
