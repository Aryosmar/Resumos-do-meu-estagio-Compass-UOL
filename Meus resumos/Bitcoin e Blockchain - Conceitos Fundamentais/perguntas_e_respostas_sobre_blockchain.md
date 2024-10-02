## Pergunta 1: Em qual contexto histórico surgiu o Bitcoin?

**Resposta:** O Bitcoin surgiu em um contexto de crise financeira global, especificamente após a crise de 2008. A desconfiança nas instituições financeiras tradicionais e a busca por uma alternativa descentralizada foram fundamentais para sua criação. Em 2008, uma pessoa ou grupo sob o pseudônimo de Satoshi Nakamoto publicou um whitepaper propondo um sistema de dinheiro eletrônico peer-to-peer, que culminou no lançamento do software do Bitcoin em 2009. A ideia era criar uma moeda que funcionasse sem intermediários, permitindo transações diretas entre os usuários.

---

## Pergunta 2: Quais as principais funções que o Bitcoin agrega?

**Resposta:** Moeda de troca, reserva de valor, meio de pagamentos.

---

## Pergunta 3: Quais as principais características que o Bitcoin agrega?

**Resposta:** Descentralizado, segurança por criptografia, registro em blockchain e engenharia de incentivo.

---

## Pergunta 4: Qual texto melhor explica as diferenças entre o sistema bancário tradicional e o Bitcoin?

**Resposta:** Em geral, o Bitcoin é baseado em consenso, descentralizado, algoritmos e controle individual do dinheiro, enquanto as operações bancárias são centralizadas, arbitrárias e baseadas em controle institucional do dinheiro dos clientes.

---

## O que acontece se esse consenso não for atingido?

**Resposta:** Se a comunidade é incapaz de atingir um consenso, é comum que ocorram os chamados “hard forks”, ou “bifurcação”. Nesse caso, cada agente do sistema Bitcoin passa a agir de acordo com o lado que apoia, e passam a existir dois Bitcoins, cada um com seu próprio sistema de regras. Foi assim que surgiram moedas como o Bitcoin Cash e o Bitcoin Gold. Grupos que não concordavam com os rumos que o Bitcoin tomava criaram novas moedas de acordo com suas visões. Como essas novas moedas têm um passado em comum com o Bitcoin original, todas as pessoas que possuíam Bitcoins antes do “fork” também passam a ter o mesmo saldo nas novas moedas. A partir do “fork”, cada moeda se torna independente, de forma que possuir Bitcoins tradicionais não dá posse de outras moedas baseadas em Bitcoin. Até meados de 2019, já ocorreram três “hard forks” no Bitcoin.

---

## O que é uma blockchain?

**Resposta:** É uma estrutura para armazenamento de dados que consiste de vários blocos conectados entre si. Um esquema criptográfico garante a inviolabilidade da cadeia.

---

## O que as funções hash fazem?

**Resposta:** As funções hash transformam um texto de entrada, de qualquer tamanho, em um texto de saída aparentemente aleatório, com tamanho fixo.

---

## Quais as características fundamentais das funções hash criptográficas?

**Resposta:** Fácil de computar, unidirecional, livre de colisão e "puzzle friendly".

---

## Como as funções hash garantem a integridade da blockchain?

**Resposta:** Cada bloco da blockchain é identificado pelo hash de seu conteúdo e também armazena o hash do bloco anterior. Se um bloco for alterado, seu hash será alterado, quebrando a cadeia de blocos.

---

## O que acontece se um hacker tentar alterar a blockchain do Bitcoin?

**Resposta:** Se um hacker tentar introduzir dados falsos na blockchain do Bitcoin, a cadeia de blocos será quebrada, tornando a fraude evidente. Para evitar isso, o hacker teria que alterar praticamente toda a blockchain. Além disso, os outros agentes da rede rapidamente detectariam que algo está errado, já que a nova cadeia que o hacker tentaria introduzir seria completamente diferente da existente. Em mais de dez anos de operação, não há registro de uma tentativa bem-sucedida de adulterar a blockchain do Bitcoin.

---

## O que acontece se alguém descobrir seu par chave pública/secreta?

**Resposta:** Se alguém descobrir seu par chave pública/secreta, essa pessoa poderá assinar qualquer documento como se fosse você. Sendo um conjunto de funções criptográficas, o sistema de assinaturas digitais não consegue distinguir entre as pessoas, apenas verifica a compatibilidade das chaves utilizadas. Proteger sua chave secreta é fundamental para a segurança no Bitcoin.

---

## Quais características a CentralCoin tem em comum com o Bitcoin?

**Resposta:** Praticamente tudo. A única diferença é que na CentralCoin existe uma autoridade central que verifica as transações e mantém a blockchain, enquanto no Bitcoin isso é feito por uma rede descentralizada.

---

## Quais informações ficam armazenadas na blockchain da CentralCoin?

**Resposta:** Transações de criação e de transferência de moedas CentralCoins.

---

## Como funciona a transação de transferência de moedas?

**Resposta:** O usuário deve indicar quais moedas está utilizando (destruindo), quais os destinatários das novas moedas criadas e adicionar sua assinatura digital.

---

## O que o Banco Central verifica em cada transação de transferência?

**Resposta:** A autenticidade da assinatura digital utilizada, se a soma das moedas consumidas é maior do que as moedas criadas e se o usuário de fato tem a posse das moedas utilizadas.

---

## Como o banco sabe o meu saldo na CentralCoin?

**Resposta:** Na CentralCoin (e no Bitcoin), o conceito de “saldo” de uma “conta” é diferente. O banco central não mantém um cadastro onde calcula quanto dinheiro cada usuário tem. O saldo de uma pessoa é a soma do valor de todas as moedas criadas e destinadas à chave pública dessa pessoa, que ainda não tenham sido consumidas em outras transações. O banco da CentralCoin verifica esses dados na blockchain para saber o “saldo” de uma chave pública.
