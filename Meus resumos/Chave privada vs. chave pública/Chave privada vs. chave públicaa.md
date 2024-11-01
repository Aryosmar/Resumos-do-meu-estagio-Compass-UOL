# Guia para Iniciantes: Chave Privada vs. Chave Pública – Como Funcionam?

Hoje, faremos uma comparação simples entre chave privada e chave pública. Depois que você entender a diferença, será capaz de compreender corretamente como a criptomoeda funciona.

Quando se trata de blockchain ou criptomoeda em geral, você deve ter ouvido falar sobre chaves privadas e públicas. Elas são parte integrante de qualquer blockchain. Sem elas, toda a ideia cairá por terra. Então, elas caem? Vamos começar.

# Chave Privada vs. Chave Pública

Antes de nos aprofundarmos na comparação, precisamos primeiro entender cada um deles. Na criptografia Blockchain, um algoritmo criptográfico sempre tem duas ou mais chaves associadas a ele: chaves privadas e públicas.

## O que é uma Chave Privada?

Uma chave privada é uma chave secreta usada para criptografar e descriptografar mensagens, em conjunto com a chave pública. Ela deve ser mantida em segredo e nunca compartilhada com ninguém.

Em criptomoedas, as chaves privadas são utilizadas por carteiras para proteger os ativos. Como não podem ser revertidas, oferecem segurança sem comprometimento.

Por exemplo, ao criar uma nova carteira Bitcoin, tanto a chave privada quanto a chave pública são geradas. Após obtê-la, é fundamental fazer um backup da chave privada em um local seguro.

**Nota:** Se você perder sua chave privada, não conseguirá acessar sua carteira ou seus fundos. Sempre faça um backup, seja escrevendo em um diário privado ou imprimindo.

# O que é uma Chave Pública?

Uma chave pública é utilizada para criptografar mensagens e pode ser enviada a outras pessoas. Após um remetente criptografar uma mensagem com a chave pública, apenas a chave privada correspondente pode desbloqueá-la.

## Tipos de Criptografia

### Criptografia Assimétrica
A criptografia assimétrica gera um par de chaves privadas e públicas. Esse algoritmo permite o envio seguro de mensagens, sendo impossível adivinhar a chave privada a partir da chave pública. As assinaturas digitais são usadas para compartilhar a chave pública, enquanto a chave privada é armazenada de forma segura.

### Criptografia Simétrica
A criptografia simétrica utiliza apenas chaves privadas, sendo útil para criptografar dados em servidores. Ambas as criptografias podem trabalhar em conjunto, onde a criptografia assimétrica é utilizada para enviar chaves privadas pela rede, mantendo-as seguras durante a transmissão.

## Funcionamento

O processo inicia quando alguém decide enviar moedas via blockchain. Como usuário, você tem acesso apenas à sua chave privada e à chave pública, que são sequências longas de números e letras. Por exemplo, uma chave de criptografia de 512 bits pode ser gerada aleatoriamente por um Gerador de Chave de Criptografia.

Após a transação ser iniciada, o blockchain gera uma assinatura para garantir que a transação ocorra sem alterações ou gastos duplos. Essa assinatura é utilizada para confirmar a transação.

# Geração da Chave Pública e Endereço

A chave pública é gerada a partir da chave privada. Em seguida, a chave pública passa por uma função hash unidirecional que produz o endereço público. Este endereço é visível para qualquer pessoa e pode ser compartilhado para receber moedas ou fundos.

## Relação entre Chave Pública, Endereço e Chave Privada

- **Geração**: Tanto a chave pública quanto o endereço podem ser gerados a partir da chave privada.
- **Irreversibilidade**: Não é possível obter a chave privada a partir do endereço público ou da chave pública. Embora tecnicamente reversível, isso exigiria mais de 40 seguido de 31 zeros anos usando os computadores mais poderosos, tornando essa possibilidade inviável e garantindo a segurança do processo.


# Conclusão

Esperamos que nosso artigo sobre chave pública vs chave privada tenha ajudado você a entender como funciona. Se você é novo em criptomoeda ou blockchain, é essencial aprender esses conceitos e compreender a importância de cada um deles. 

**Cuidados com a Chave Privada**: Como usuário, você deve proteger sua chave privada a todo custo. Nunca a compartilhe com ninguém, pois isso pode resultar na perda de seus fundos. Esteja atento a golpes online que tentam obter sua chave privada. Se alguém solicitar, não hesite em ignorar e se afastar da situação!
