# O Ethereum – Gas – Aula 19

## 1. O que é o gas no Ethereum?

- O **gas** no Ethereum é uma unidade que mede o custo computacional necessário para executar operações na rede. Ele é necessário para processar transações e rodar contratos inteligentes.

---

## 2. Por que o gas é importante?

- O gas garante que cada transação ou execução de contrato inteligente tenha um custo associado, protegendo a rede contra abusos, como **loops infinitos** ou **ataques de negação de serviço (DDoS)**, nos quais programas inúteis poderiam sobrecarregar os nós da rede.

---

## 3. Como o gas resolve o problema da ineficiência na execução de código em todos os nós da rede?

- Ao exigir que os usuários paguem por cada operação realizada, o gas desincentiva a criação de programas ineficientes e evita que códigos maliciosos ou ineficazes sobrecarreguem a rede.

---

## 4. Como funciona o pagamento com gas?

- Cada transação na rede Ethereum deve incluir uma quantidade de gas. Se a transação ou execução de um contrato inteligente for simples, o gas necessário será menor; se for mais complexa, mais gas será necessário.

---

## 5. O que acontece se o gas acabar durante a execução de um contrato inteligente?

- Se o gas acabar antes que o contrato seja totalmente executado, a operação é interrompida, e os nós da rede reverterão a transação sem que ela seja finalizada.

---

## 6. O que é o gas limit?

- O **gas limit** é o máximo de gas que uma transação pode consumir. Isso limita a complexidade dos contratos inteligentes, impedindo que eles utilizem mais recursos do que o permitido.

---

## 7. Qual é a relação entre o gas e o éter (ETH)?

- O gas é comprado com **éter (ETH)**, a criptomoeda nativa do Ethereum. Quando uma transação é enviada, o usuário paga o gas necessário em éther.

---

## 8. Por que o preço do gas varia?

- O preço do gas pode variar com base na **demanda da rede**. Quando há muitos usuários tentando processar transações ao mesmo tempo, o preço do gas aumenta, e as transações mais urgentes tendem a pagar mais para serem processadas mais rapidamente.

---

## 9. Como o gas incentiva a eficiência dos programadores?

- Como o custo para rodar código depende da quantidade de gas, os desenvolvedores são incentivados a criar contratos inteligentes mais eficientes, que consumam menos gas e, consequentemente, custem menos para serem executados.

---

## 10. Como o gas protege a rede contra ataques de DDoS?

- Como cada operação tem um custo, um ataque que tentasse inundar a rede com transações inúteis seria financeiramente insustentável, já que o atacante teria que pagar por cada operação realizada.

---

## 11. O que é um loop infinito e como o gas o previne?

- Um **loop infinito** é um erro de programação onde uma operação continua a ser executada indefinidamente. O gas impede que loops infinitos travem a rede, pois a execução para automaticamente quando o gas é totalmente consumido.
