# Sistema Bancário Avançado

Este é um projeto de um sistema bancário avançado em Python que permite aos usuários realizar depósitos, saques, criar novas contas e usuários, listar contas e visualizar o extrato. O sistema possui um menu interativo e mantém o saldo e as transações dos usuários.

## Funcionalidades

- **Depositar**: Permite ao usuário adicionar um valor ao saldo.
- **Sacar**: Permite ao usuário retirar um valor do saldo, respeitando o limite diário de saques e o limite de valor por saque.
- **Extrato**: Exibe todas as transações realizadas e o saldo atual.
- **Nova conta**: Permite criar uma nova conta bancária para um usuário existente.
- **Listar contas**: Lista todas as contas bancárias cadastradas.
- **Novo usuário**: Permite criar um novo usuário.
- **Sair**: Encerra o programa.

## Limitações

- Limite de saque por transação: R$ 500,00
- Limite diário de saques: 3 saques
- Não é permitido realizar operações com valores negativos ou nulos

## Como Usar

1. Clone este repositório.
2. Abra o terminal e navegue até o diretório do projeto.
3. Execute o script Python:

```sh
python sistema_bancario_funcoes.py
