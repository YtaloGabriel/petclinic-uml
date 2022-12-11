## Caso de Uso 03

### Gerenciar folha de pagamento
#### Ator: Administrador

#### Fluxo Normal:
1. Autenticar Administrador
2. Administrador informa o tipo de pagamento (salário ou demais gastos)
3. Administrador informa o valor do pagamento
4. Administrador envia as informações para o sistema

#### Extensões:
- 1.1. Se o Administrador não estiver autenticado, solicitar um logn válido.
- 2.1. Se o Administrador selecionar a opção "salário", solicitar que ele adicione o CPF do Funcionário.
- 2.2. Se o Administrador selecionar a opção "salário" e digitar um CPF inválido, solicitar que ele digite um CPF existente.
- 2.3. Se o Administrador selecionar a opção "demais gastos", solicitar que ele adicione o nome do gasto.
- 2.4. Se o Administrador selecionar a opção "demais gastos" e adicionar um nome já existente, informar que já existe um gasto com esse nome.
- 3.1. Se o Administrador informar um gasto menor ou igual a 0, solicitar que ele adicione um número de gasto válido.
