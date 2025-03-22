# Desafio: Sistema Bancário com Python

## Descrição
Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguagem Python. Para a primeira versão do sistema, devemos implementar apenas três operações: **depósito, saque e extrato**.

## Funcionalidades

### 1. Operação de Depósito
- Deve ser possível depositar valores positivos na conta bancária.
- A primeira versão do sistema trabalha apenas com um único usuário, portanto, não há necessidade de identificar agência e conta bancária.
- Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

### 2. Operação de Saque
- O sistema deve permitir realizar **até 3 saques diários**, com um **limite máximo de R$ 500,00 por saque**.
- Caso o usuário **não tenha saldo suficiente**, o sistema deve exibir uma mensagem informando que o saque não pode ser realizado.
- Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

### 3. Operação de Extrato
- Deve listar todos os **depósitos e saques** realizados na conta.
- No fim da listagem, deve ser exibido o **saldo atual da conta**.
- Os valores devem ser exibidos no formato: `R$ xxx.xx`.

Exemplo de exibição:
```
Depósito: R$ 1500.45
Saque: R$ 300.00
Saque: R$ 200.00

Saldo atual: R$ 1000.45
```

## Tecnologias Utilizadas
- Linguagem: **Python**

## Autor
Desenvolvido port Joberth Castro para um desafio de implementação de um **sistema bancário básico** em Python.
