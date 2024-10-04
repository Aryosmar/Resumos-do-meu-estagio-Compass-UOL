# Aula 6 - O Bitcoin - Sessão 2

## A Rede Bitcoin

No Bitcoin, o papel do Banco Central é feito por uma rede de computadores distribuída, sem hierarquia. Isso significa que não há um computador central controlando a rede, e todos os computadores conectados a ela são iguais. Esses computadores se conectam entre si diretamente, sem precisar de um servidor ou computador central. Cada computador na rede é chamado de "nó", e esses nós precisam se comunicar para entrar em acordo sobre as transações, mesmo que alguns possam ser maliciosos (hackers). A segurança da rede precisa ser garantida independentemente disso.

## Como Participar da Rede Bitcoin

Qualquer pessoa pode participar da rede Bitcoin baixando um "Bitcoin Client", um conjunto de informações que pode ser obtido diretamente do site do Bitcoin. Usuários comuns geralmente não baixam esse cliente diretamente, preferindo usar softwares que fazem isso automaticamente, mas você pode optar por rodar o cliente em seu próprio computador e se conectar à rede Bitcoin como um nó.

## Blockchain e os Tipos de Nós

A blockchain do Bitcoin é única e está distribuída entre todos os nós da rede, sendo idêntica para todos. Existem dois tipos principais de nós na rede:

1. **Full Nodes (Nós Completos)**: Esses nós têm uma cópia completa da blockchain e realizam funções essenciais para o funcionamento da rede, como a validação de transações e de novos blocos criados pelos mineradores.
2. **Lite Nodes (Nós Leves)**: Esses nós possuem apenas uma parte da blockchain e precisam consultar os Full Nodes para obter informações adicionais quando necessário. Mineradores geralmente são Full Nodes, enquanto carteiras podem ser Lite Nodes.

## O Processo de Transações

Quando o José quer transferir bitcoins para a Maria, ele assina digitalmente a transação, informando quais moedas está usando e criando novas para o pagamento. Ao invés de enviar isso para um Banco Central, ele envia para um nó da rede Bitcoin, que valida a transação e a propaga para os demais nós através de um protocolo chamado "Protocolo de Fofoca". Esse protocolo faz com que a transação se espalhe rapidamente entre os nós.

## A Importância dos Mineradores

Como a rede é distribuída e não há um nó central, mineradores desempenham o papel de validar e registrar transações na blockchain. Eles competem entre si para ver quem terá o direito de adicionar o próximo bloco à blockchain. Cada bloco contém várias transações (com limite de até 1 MB), e os mineradores montam blocos diferentes com as transações de que têm conhecimento.

Quando um minerador finaliza um bloco, ele avisa os outros mineradores, que verificam se o bloco está correto. Se estiver, esse bloco é adicionado à blockchain, e a competição começa novamente para o próximo bloco.

## Questionário para Fixar o Conteúdo

1. **Quais as características da rede Bitcoin?**
   - Distribuída, sem hierarquia, segue um protocolo de consenso.

2. **O que é um nó da rede Bitcoin?**
   - É qualquer computador que esteja conectado à rede Bitcoin.

3. **O que diferencia um full node de um lite node?**
   - O full node, em geral, armazena toda a blockchain e é capaz de operar independentemente.

4. **Como a blockchain garante consenso na rede Bitcoin?**
   - As transações de Bitcoin só se tornam efetivas quando são inseridas na blockchain, e a mineração garante que todos os nós mantenham a mesma blockchain armazenada.

5. **O que acontece se um nó da rede começa a transmitir informações falsas?**
   - Nada. A rede Bitcoin é extremamente resistente a agentes maliciosos, porque todas as informações são verificadas antes de serem adicionadas na blockchain, e a partir daí tornam-se impossíveis de adulterar. Para adicionar informações falsas na blockchain, um hacker teria que ter ao menos 51% de todo o poder computacional da rede, algo extremamente improvável para o Bitcoin. Em criptomoedas pouco conhecidas e com poucos mineradores, este é um risco significativo. Outra possibilidade é o hacker roubar a chave secreta de um usuário, quando então poderá assumir a identidade (e os Bitcoins) da vítima, transferindo-os para onde quiser. Nesse caso, a falha de segurança não é na rede Bitcoin, já que as informações fornecidas são tecnicamente verdadeiras e a rede não é capaz de identificar quem as está transmitindo. Seria como se alguém tivesse roubado seu talão de cheques e soubesse imitar sua assinatura perfeitamente, sem a possibilidade de estornar os cheques utilizados.
