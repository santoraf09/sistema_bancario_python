# Sistema Bancário Simples

Este é um sistema bancário simples em Python que permite aos usuários realizar operações bancárias básicas, como depósito, saque, visualização de extrato, criação de contas e usuários.

## Funcionalidades

- **Depósito**: Permite ao usuário depositar um valor em sua conta.
- **Saque**: Permite ao usuário sacar um valor de sua conta, com verificações de saldo, limite e número de saques permitidos.
- **Extrato**: Exibe o extrato das operações realizadas e o saldo atual da conta.
- **Nova Conta**: Cria uma nova conta para um usuário existente.
- **Listar Contas**: Lista todas as contas criadas com suas respectivas informações.
- **Novo Usuário**: Cria um novo usuário no sistema.

## Como usar

1. Clone este repositório para sua máquina local:
   ```sh
   git clone https://github.com/santoraf09/sistema-bancario-simples.git

## Estrutura do Código

- **exibir_menu()**: Exibe o menu principal do sistema.
- **depositar(saldo, valor, extrato)**: Realiza a operação de depósito.
- **sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)**: Realiza a operação de saque.
- **exibir_extrato(saldo, extrato)**: Exibe o extrato da conta.
- **criar_usuario(usuarios)**: Cria um novo usuário.
- **filtrar_usuario(cpf, usuarios)**: Filtra um usuário pelo CPF.
- **criar_conta(agencia, numero_conta, usuarios)**: Cria uma nova conta para um usuário existente.
- **listar_contas(contas)**: Lista todas as contas criadas.
- **main()**: Função principal que controla o fluxo do sistema.
