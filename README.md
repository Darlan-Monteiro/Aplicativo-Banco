# Aplicativo-Banco
Este é um sistema bancário simples desenvolvido em Python que permite aos usuários realizar operações bancárias básicas, como login, consulta de saldo, depósito, saque e transferência. Os dados dos usuários, senhas e saldos são armazenados em arquivos CSV.



## Funcionalidades

- **Login**: Verifica as credenciais do usuário a partir de um arquivo CSV.
- **Saldo**: Consulta o saldo disponível do usuário.
- **Depósito**: Permite ao usuário depositar valores em sua conta, respeitando o limite máximo de R$ 5.000.
- **Saque**: Permite ao usuário retirar valores de sua conta, respeitando o limite máximo de R$ 5.000 e o saldo disponível.
- **Transferência**: Permite ao usuário transferir valores para outro usuário, respeitando o limite máximo de R$ 5.000 e o saldo disponível.

## Requisitos

- Python 3.x
- Biblioteca `pandas`
