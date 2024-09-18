# Fin API - Financeira

## Requisitos 

- [] Deve ser possível criar uma conta
- [] Deve ser possível buscar o extrato bancário do cliente
- [] Deve ser possível realizar um depósito
- [] Deve ser possível realizar um saque
- [] Deve ser possível realizar uma transferência via pix
- [] Deve ser possível buscar o extrato bancário do cliente por data
- [] Deve ser possível atualizar os dados da conta do cliente
- [] Deve ser possível obter os dados da conta do cliente
- [] Deve ser possível deletar uma conta

## Regras de negócio

- [] Não deve ser possível cadastrar uma conta com CPF já existente
- [] Não deve ser possível fazer depósito em uma conta não existente
- [] Não deve ser possível buscar o extrato de uma conta não existente 
- [] Não deve ser possível fazer um saque em uma conta não existente
- [] Não deve ser possível fazer um pix de/para uma conta não existente
- [] Não deve ser possível excluir uma conta não existente
- [] Não deve ser possível fazer um saque quando o saldo for insuficiente
- [] Não deve ser possível fazer um pix para si mesmo
- [] Não deve ser possível fazer um pix quando o saldo for insuficiente
- [] Não deve ser possível fazer um pix acima do limite permitido
