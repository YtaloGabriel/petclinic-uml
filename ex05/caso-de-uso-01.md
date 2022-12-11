## Caso de Uso 01

### Cadastrar Medicamentos
#### Ator: Funcionário

#### Fluxo Normal:
1. Autenticar funcionário
2. funcionário informa o nome genérico do medicamento
3. funcionário informa a via de administração do medicamento
4. funcionário informa a forma farmacêutica do medicamento
5. funcionário informa o preço do medicamento
6. funcionário informa a quantidade em estoque do medicamento
7. funcionário efetua o cadastro do medicamento
8. sistema adiciona o medicamento no banco de dados e limpa os campos para que um novo medicamento seja adicionado

#### Extensões:
- 1.1. Se o funcionário não for autenticado, solicitar um login válido 
- 2.1. Se a medicação já existir no sistema, informar que o medicamento já está cadastrado 
- 5.1. Se o valor inserido for menor que 0, solicitar um preço válido. 
- 5.2. Se o valor inserido for igual a 0, perguntar se o medicamento é realmente gratuito.
- 6.1. Se o valor inserido for menor ou igual a 0, solicitar um estoque válido. 
