# Ethereum - Accounts e States

## 1. Qual é o primeiro aspecto do funcionamento da rede Ethereum?

- O primeiro aspecto é o funcionamento das contas dentro da rede, que podem ser controladas por humanos ou por contratos inteligentes.

---

## 2. O que significa o Ethereum ser uma máquina de estados?

- Significa que o Ethereum é baseado em contas e no estado dessas contas, que mudam conforme as transações acontecem na rede.

---

## 3. Quais são os dois tipos de contas no Ethereum?

- Existem dois tipos de contas no Ethereum: 
  - **Externally Owned Accounts (EOA)**: controladas por humanos através de chaves privadas.
  - **Contract Accounts**: controladas por contratos inteligentes.

---

## 4. O que são Externally Owned Accounts (EOA)?

- Externally Owned Accounts são contas controladas por usuários externos, ou seja, pessoas, que gerenciam a conta através de sua chave privada.

---

## 5. O que são Contract Accounts?

- Contract Accounts são contas controladas por códigos de contratos inteligentes, que também possuem saldo e são capazes de realizar transações.

---

## 6. Como as contas no Ethereum diferem das contas no Bitcoin?

- No Bitcoin, o saldo é determinado pelas transações não gastas (UTXOs). No Ethereum, cada conta tem um saldo contínuo, que é atualizado a cada novo bloco de transações, de forma mais intuitiva e similar a uma conta bancária.

---

## 7. Como o saldo de uma conta é atualizado no Ethereum?

- Toda vez que um novo bloco com transações é adicionado, o estado da conta é atualizado. Se houver uma transação relacionada à conta, o saldo muda; caso contrário, ele permanece o mesmo.

---

## 8. As Contract Accounts no Ethereum também possuem saldo?

- Sim, assim como as contas de usuários, as Contract Accounts também possuem um saldo e podem armazenar valores, como uma máquina de refrigerantes que pode armazenar dinheiro.

---

## 9. O que é a estrutura de dados chamada "state" (ou Merkle Patricia Tree) no Ethereum?

- O **state** (ou Merkle Patricia Tree) é a estrutura de dados que armazena o estado de todas as contas no Ethereum, permitindo que cada nó da rede mantenha esses estados atualizados com a chegada de novos blocos.

---

## 10. Por que o Ethereum utiliza o modelo de contas e estados?

- O Ethereum escolheu esse modelo por simplicidade conceitual, facilitando o entendimento e a programação de contratos inteligentes, além de ser mais eficiente do que o sistema de transações não gastas (UTXOs) do Bitcoin.

---

## 11. Como a simplicidade do modelo de contas facilita a criação de programas no Ethereum?

- A simplicidade de lidar com estados de contas torna mais intuitivo para os desenvolvedores programarem contratos inteligentes, já que não precisam lidar com transações não gastas, como no Bitcoin.

---

## 12. Por que a eficiência computacional é importante para o Ethereum?

- A rede Ethereum precisa ser computacionalmente eficiente para lidar com a execução de contratos inteligentes e a atualização constante dos estados de contas, o que torna o modelo de contas mais eficiente que o sistema UTXO.
