# Bitcoin e Blockchain: Revisão

## 1. Funções Criptográficas
- Aprendemos como funcionam as funções de hash criptográficas.
- Elas são fundamentais para garantir a segurança das transações e blocos no Bitcoin.

## 2. Blockchain
- A blockchain é uma cadeia de blocos, onde cada bloco contém dados das transações e o hash do bloco anterior.
- Cada bloco tem um identificador único (hash) calculado com base em todos os dados dentro do bloco.

## 3. Assinaturas Digitais
- As assinaturas digitais garantem a autenticidade das transações.
- São usadas para verificar se quem está enviando a transação é de fato o dono dos bitcoins.

## 4. Transações
- As transações no Bitcoin seguem um esquema descentralizado.
- Mineradores competem para validar e adicionar essas transações à blockchain.

## 5. Protocolo Proof of Work (PoW)
- Mineradores competem para encontrar um hash que comece com um determinado número de zeros.
- Para encontrar esse hash, eles ajustam o "nonce" (um número arbitrário) várias vezes até obter o hash correto.
- A dificuldade de encontrar esse hash é ajustada para que um novo bloco seja encontrado a cada 10 minutos.

## 6. Propriedades das Funções Hash Criptográficas
- **Fácil de Computar**: Mineradores podem calcular rapidamente o hash e verificar se o resultado está correto.
- **Unidirecionalidade**: É difícil descobrir o input a partir do hash.
- **Avalanche (Efetividade)**: Pequenas mudanças no input causam grandes mudanças no hash.

## 7. Validação e Consenso
- Quando um minerador encontra o hash correto, ele compartilha o novo bloco com a rede.
- Se outros mineradores concordarem que o bloco é válido, ele é adicionado à blockchain.
- O consenso é implícito: se outros mineradores começam a minerar no novo bloco, significa que o aprovaram.

## 8. Recompensa dos Mineradores
- Mineradores são recompensados por meio de tarifas de transação e a criação de novos bitcoins através da "Coinbase Transaction".
- A recompensa por minerar um bloco diminui pela metade a cada 4 anos, limitando o número total de bitcoins a 21 milhões.

## 9. Pools de Mineração
- Devido à alta dificuldade, mineradores formam pools, onde trabalham juntos para encontrar blocos e compartilham as recompensas proporcionalmente ao esforço.
- As pools otimizam a mineração e podem minerar várias criptomoedas, selecionando a mais lucrativa em cada momento.

## 10. Equipamento Especializado
- A mineração de Bitcoin requer hardware especializado (ASICs), que consome muita energia.
- A mineração de Bitcoin consome atualmente 0,16% da eletricidade mundial.

# Questionário

### O que é um nonce e qual a função dele?
- O nonce é um valor numérico sem significado que é adicionado a cada bloco da blockchain. Os mineradores alteram o valor do nonce tentando cumprir com o requisito do proof of work.

### O que dá ao minerador o direito de adicionar o próximo bloco da cadeia?
- Conseguir criar um bloco cujo hash tenha um determinado número de zeros.

### De onde surgiram os Bitcoins em circulação?
- Todos os Bitcoins em circulação surgiram da mineração. A cada quatro anos, o número de Bitcoins criados a cada novo bloco é reduzido pela metade.

### O que são mining pools?
- São esquemas cooperativos entre mineradores, em que todos trabalham tentando montar blocos, e os Bitcoins auferidos são distribuídos entre todos os participantes de acordo com o trabalho computacional de cada um.

### Já que a recompensa pela mineração vem caindo com o tempo, pode ser que no futuro haja bem menos mineradores. Qual é a consequência disso para a velocidade de criação de novos blocos?
- Nenhuma. Um novo bloco é criado, em média, a cada dez minutos. Se o número de mineradores é menor, fica mais fácil obter uma solução para o proof of work. Assim, a taxa de criação de blocos é mantida aproximadamente constante.
