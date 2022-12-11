# Tabelas de Classes

### Classe 1
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| Funcionario | nomeFuncionario: String | gerenciarMedicamento() |
| | cpfFuncionario: String | gerenciarAgenda() |
| | codigoFuncionario: String | |
| | salarioFuncionario: Float | gerenciarCliente() |
| | | gerenciarAtendimento() |

### Classe 2
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| Cliente | nomeCliente: String      | verAgenda()    |
| | idadeCliente: String | realizarAgendamento() |
| | codigoCliente: String | |
| | pesoCliente: Float | |
| | racaCliente: String | |
| | nomeTutor: String | |
| | telefoneTutor: String | |

### Classe 3
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| Agenda | nomeAgenda: String | |
| | dataAgenda: Datetime | |
| | codigoCliente: String | |
| | codigoFuncionario: String | |

### Classe 4
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| Atendimento | nomeAtendimento: String | |
| | tipoAtendimento: String | |
| | tempoMedioDeAtendimento: String | |


### Classe 5
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| HistoricoConsultas | codigoConsulta: String | |
| | tipoConsulta: String | |
| | codigoCliente: String | |
| | dataConsulta: Datetime | |
| | codigoFuncionario: String | |


### Classe 6
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| HistoricoClientes | codigoCliente: String | |

### Classe 7
|    Classe   |     Atributos     |           Métodos         |
| ----------- | ----------------- | ------------------------- |
| FolhaDePagamento | tipoPagamento: String | |
| | codigoFuncionario: String | |
| | precoPagamento: Float | |
