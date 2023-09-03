# Sistema Bancário em Python

## Objetivo Geral
Desenvolver um sistema bancário que permita ao usuário realizar operações básicas, como sacar, depositar e visualizar o extrato de sua conta.

## Desafio
Fomos contratados por um renomado banco para projetar seu novo sistema bancário. Com a missão de modernizar suas operações, o banco escolheu a linguagem Python para tal feito. A versão inicial (v1) deste sistema terá o foco em três operações principais: depósito, saque e visualização do extrato.

### Operação de Depósito
- O usuário pode depositar valores positivos em sua conta bancária.
- Nesta versão inicial, estamos trabalhando apenas com um usuário, por isso não há necessidade de identificar número de agência ou conta bancária.
- Todos os depósitos serão armazenados em uma variável e listados na operação de extrato.

### Operação de Saque
- Os usuários podem realizar até 3 saques diários.
- O valor máximo para cada saque é de R$ 500,00.
- Se o usuário não tiver saldo suficiente, o sistema irá informar que o saque não é possível devido à insuficiência de fundos.
- Todos os saques serão armazenados em uma variável e listados na operação de extrato.

### Operação de Extrato
- Esta funcionalidade exibirá todos os depósitos e saques realizados na conta.
- Ao final da lista de transações, o saldo atual da conta será mostrado.
- Se nenhum saque ou depósito tiver sido feito, o sistema exibirá a mensagem: "Não foram realizadas movimentações".

---

Para obter mais informações ou relatar problemas, consulte a seção de *Issues* deste repositório no GitHub. Agradecemos por escolher nosso projeto e esperamos atender suas expectativas!
