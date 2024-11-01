# Uso de Criptografia em Criptomoeda: Guia para Iniciantes

Este artigo explica o que é criptografia em criptomoedas e como ela protege blockchains contra hackers.

Se você é um trader de criptomoedas ou um desenvolvedor de blockchain-criptomoeda, então você já ouviu duas alegações:
1. A primeira é que a criptografia de chave privada-chave pública mantém as transações seguras.
2. A segunda é que a criptografia mantém as redes de blockchain seguras.

Depois de ler este artigo, os traders de criptomoedas saberão como proteger sua chave privada para manter suas transações de criptomoedas seguras. Os desenvolvedores de blockchain-criptomoeda saberão que, desde que usem um algoritmo criptográfico padrão, sua rede de blockchain estará segura.

A criptografia moderna depende muito de matemática avançada, e uma explicação desses conceitos matemáticos está além do escopo deste artigo.

# Hackear Criptomoedas: Quais São os Riscos?

Há dois eventos que podem causar perdas para os traders de criptomoedas e para uma rede de criptomoedas blockchain:

1. Hackers quebram a assinatura digital do trader de criptomoedas e iniciam transações maliciosas a partir da conta do trader.
2. Hackers comprometem a rede blockchain subjacente a uma criptomoeda e manipulam transações nela.

A criptografia, que é um resultado da criptografia moderna, protege a assinatura digital do trader de criptomoedas. Além disso, funções de hash criptográficas protegem a rede blockchain.

# O Que É uma Função Hash Criptográfica?

Uma 'função hash' converte um conjunto de dados de comprimento variável em uma sequência alfanumérica de tamanho fixo. Na ciência da criptografia, algumas funções hash específicas são usadas, e estas são chamadas de 'funções hash criptográficas'. As funções hash criptográficas têm certas características específicas, e estas são as seguintes:

- **Determinísticas**: Uma entrada específica sempre produz a mesma saída.
- **Sensibilidade a Alterações**: Mesmo que a entrada seja alterada marginalmente, o hash de saída será drasticamente diferente.
- **Cálculo Rápido**: O cálculo do valor de hash é rápido.
- **Irreversibilidade**: Calcular a entrada do hash é praticamente impossível devido à extrema dificuldade.

Funções de hash criptográficas são usadas no contexto do blockchain para produzir a assinatura digital dos usuários usando a criptografia da chave pública-privada. Essas funções também são usadas para identificar exclusivamente cada bloco no blockchain de forma embaralhada, de modo que o conteúdo do bloco não possa ser reproduzido usando o hash.


# Como a Criptografia de Chave Pública-Privada Protege as Transações dos Comerciantes de Criptomoedas?

Os traders de criptomoedas têm chaves públicas que eles compartilham com outros para que possam receber criptomoedas. Essa chave pública também é conhecida como endereço do usuário. Pelo contrário, os usuários não devem compartilhar suas chaves privadas. Eles devem protegê-las, porque, se um hacker obtiver a chave privada, o trader de criptomoedas pode perder todos os seus fundos.

A chave pública é apenas um hash criptográfico da chave privada. É muito fácil gerar a chave pública a partir da chave privada; no entanto, é praticamente impossível fazer o oposto.

Para enviar suas transações aos mineradores, os traders de criptomoedas realizam os seguintes passos:

1. **Criar um hash criptográfico** da mensagem da transação por meio de uma função de hash criptográfico.
2. **Executar o hash e a chave privada** por meio de um algoritmo de assinatura.
3. **Enviar** a chave pública, a mensagem e a assinatura digital gerada pelo algoritmo de assinatura.

Quando os mineradores recebem as transações, eles realizam os seguintes passos:

1. **Executar a mensagem recebida** por meio de uma função de hash criptográfico.
2. **Executar a assinatura recebida e a chave pública** por meio de um algoritmo de verificação de assinatura, que produz um hash.
3. Os mineradores então **comparam os dois hashes**; se eles corresponderem, a transação é válida.


# A Criptografia de Chave Pública-Privada é Segura?

Se hackers adulterassem a transação do trader de criptomoedas, eles precisariam primeiro mudar a mensagem de acordo com sua necessidade antiética e, em seguida, encontrar uma assinatura digital que correspondesse ao hash. Lembre-se de que as funções de hash criptográficas são "unidirecionais". Os hackers precisam passar por um longo processo de tentativa e erro para encontrar uma assinatura dessas.

**Quanto tempo?** Bem, para hackear uma assinatura digital na rede blockchain, usando todo o poder de computação da rede, o hacker precisaria de 5 "quindecilhões" (1 quindecilhões = 10^48) anos! 

Os traders de criptomoedas podem ficar tranquilos, a criptografia de chave pública-privada é realmente segura.


# Como o Hash de um Bloco Protege a Rede Blockchain?

Um bloco simples em uma blockchain contém as seguintes informações:

- Hash do bloco anterior;
- Detalhes das transações;
- Endereço do minerador que resolveu o bloco;
- Um número aleatório, essencial para criar um hash deste bloco.

O próximo bloco terá o hash deste bloco, e assim por diante.

Agora, suponha que um grupo de hackers planejou introduzir um novo bloco entre o 7º e o 8º bloco, para registrar algumas transações que os beneficiarão de forma antiética. Se eles criarem esse novo bloco, ele será rejeitado imediatamente pela rede devido aos seguintes motivos:

1. **Aceitação de Blocos**: Os mineradores só aceitam blocos com pequenos valores de hash, ou seja, muitos zeros iniciais.
2. **Validação do Hash**: O 'novo' 8º bloco não terá o valor de hash do 7º bloco.

Agora, os hackers precisarão resolver esses dois problemas. Encontrar um pequeno valor de hash é tremendamente difícil e requer muitas tentativas e erros. Além disso, ainda mais difícil é o segundo problema!

Os hackers terão que usar seus poderes de computação para resolver o 8º bloco para que ele comece com o hash do 7º bloco. Isso é muito difícil e requer muito poder de computação. Além disso, assim que os hackers resolverem esse problema e criarem o 'novo' 8º bloco, eles precisarão mudar o que agora é o 9º bloco, para introduzir o hash do 'novo' 8º bloco em seu 'início'. Eles precisam fazer isso para cada bloco subsequente também!


# Hackear uma Rede Blockchain é Praticamente Impossível!

Agora, considere o fato de que a rede blockchain tem milhares de mineradores, todos simultaneamente tentando minerar novos blocos. No momento em que os hackers manipulam os blocos mais cedo na cadeia, muitos mais blocos novos foram adicionados à cadeia, um após o outro.

Para os hackers, é uma cadeia interminável de tentativas de modificar blocos existentes. É praticamente impossível, a menos que os hackers consigam reunir mais poder de computação do que toda a rede blockchain. Além disso, essa atividade incomum visando blocos no início da cadeia deve alertar os outros mineradores e os hackers serão descobertos em pouco tempo.

## Considerações Finais

Se você é um trader de criptomoedas, certifique-se de manter sua chave privada segura. Se você é um desenvolvedor, use um algoritmo criptográfico padrão em seu blockchain. A criptografia moderna fará o resto.
