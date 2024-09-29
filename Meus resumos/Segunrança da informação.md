# Módulo 0 - Pilares e as políticas de Segurança da informação

## **O que é segurança da informação?**

De acor com NIST (National institute of Standards and Technology) a segurança da informação é a prontenção de informações e sistemas de informação contra o acesso, o uso, a divulgação, a interrupção, a modificação ou a destruição não autorizado, a fim de fornecer confidencialidade, integridade e disponibilidade.
 
# **Os pilares de segurança da informação**

A triade dos pilares de segurança da informação é o conjunnto de tecnologias, processos e politicas que tem como finalidade manter as informação confidenciais integras e disponíveis.

A segurança da informação tem o papel de proteger os dados agregando valor e contribuindo para o sucesso do negocio , e você tem papel fundamental  nessa missão.

## **Confidencialidade**

Para proteger a informação de acessos não autorizados, evitando situação de ataques por acesso indevido.

O objetivo é controlar o acesso por mútiplos fatores autenticação e criptografias.

## **É assim o dia a dia em autenticação !**

. Especificar requisitos minimos para uma senha segura.
.  Autenticação multifator.
. Verificação e gerenciador de sessões.

## **Integridade** 

Este é o pilar que devemos atender para manter as características originais dos dados, conforme sua criação.

A implementação de controles para impedir a alteração não autorizada devem ser pensados e implementados.


## **Original e confiável é a regra aqui!**

. Validação de dados, como hashes.
. Verificação de duplicidade.
. Tratamentos de dados de entrada, como características especias e comandos.

## **Disponibilidade** 

Queremos que os dados estejam disponíveis para o que for necessário, quando precisamos.  Isso demanda a estabilidade e acesso permanente ao ambiente e aos sistemas.

Pense aqui nos controles existentes para acessar e usar informações.

## **A qualquer hora que precise!**

. Recursos de redundâncias, como backup de dados e balanceamento de carga.
. Infraestrutura em nuvem.
. Gestão de vulnerabilidades.

## **Politica de Segurança da Informação (Psi)**

Em nossa PSI você encontra as bos práticas a seguir para proteger as informações,
tudo que estiver contrário a isso considere um incidente de segurança e deve ser reportado ao time InfoSec (veremos nos módulos a seguir).

**Nós, assim como todas as demais empresas do grupo, seguimos atualmente as orientações da PSI publicada pelo Grupo UOL  que diz.**

“A politica de segurança da informação e segurança cibernética pretende descrever as melhores práticas de segurança da informação 
e segurança cibernética quanto á confidencialidade, integridade e disponibilidade de informações; 
estabelecer diretrizes para todos os usuários, e minimizar os riscos de segurança ”


## **Politica de Classificação da Informação**

Para definir o controle mais adequado é necessário conhecer o tipo de informação a sua criticidade e o público.

O melhor guia é a politica de classificação da informação.

“Esta politica descreve o processo de classificação da informação, caracterizado pela definição do nível de sensibilidade e os grupos de acesso á informação, visando assegurar que esta receber um nível adequado de proteção,conforme seu valor, sensibilidade e criticidade para organização. ”

# Módulo 1 - Classificação da Informação

**A classificação da informação tem como obtivo definir níveis de proteção que cada informação deve receber**.

Toda e qualquer informação de ser classificada, seja física ou logica, de acordo com sua sensibilidade, criticidade e valor. A classificação deve tratar as informações durante o seu ciclo de vida, ou seja, sua criação, edição, compartimento,armazenamento e descarte.

## **Por que classificar?**

Para aplicar a devida proteção das informações e reduzir a probabilidade de ocorrer incidentes.

O vazamento de informações, por exemplo pode ocasionar impactos financeiro, regulatório e reputacional , trazendo sanções e prejuízos a Compass, seus clientes, parceiros e profissionais.

## **Confidencial**

São informações altamente sigilosas e que não podem ser divulgadas para evitar danos à empresa, terceiros, funcionários e clientes.
Seu uso requer medidas de controle e proteção rigorosos contra acessos, cópias, reproduções ou divulgações não autorizados.
Devido à sensibilidade dessas informações, várias restrições de uso são aplicadas e o destinatário consegue apenas consultar o documento.
Restrita
São informações exclusivas de alguns profissionais e/ou determinadas áreas. Significa que nem todos têm acesso a elas, pois os dados desta categoria são disponibilizados apenas aos destinatários nos quais você delega confiança para tratar do assunto.
Exemplos:
    
  - E-mail com feedback;
  - Divulgação de metas e resultados institucionais;
  - Informações sobre produtos, serviços e projetos;
  - Dados ou informações referentes às políticas comerciais.

## **Interna**

São informações que competem aos profissionais, estagiários, prestadores de serviços da empresa e precisam de cuidados para evitar a divulgação ao público externo.
Exemplos:
    • Comunicados;
    • Políticas e normas corporativas;
    • Procedimentos operacionais e técnicos;
    • Relação de endereços de e-mail internos;
    • Informações disponibilizadas na Intranet.

## **Pública**

Informações que podem ser divulgadas sem restrição ao público em geral, incluindo clientes, fornecedores e concorrentes. Esses dados não oferecem risco à empresa, colaboradores ou clientes.


# Módulo 2 - Engenharia Social

A Engenharia Social é a habilidade de obter acesso a informações importantes por meio da persuasão. O atacante explora a falta de conhecimento e a boa vontade da vítima para convencê-la a fornecer informações ou realizar ações que parecem legítimas.


A engenharia social funciona porque os seres humanos, por natureza, confiam e cooperam. Qualquer pessoa pode ser levada a compartilhar informações devido a características como curiosidade, ambição e necessidade de se sentir útil. Além disso, os investimentos em proteção de informações estão aumentando, mas os fraudadores ainda exploram a vulnerabilidade humana, que muitas vezes é negligenciada nos processos de segurança das empresas.


## **Tácticas de abordagem**

Baiting: Uso de iscas físicas ou digitais, como pendrives ou downloads, para introduzir malware no computador, permitindo acesso oculto
Phishing: Criação de conteúdo enganoso que se parece legítimo para obter credenciais ou instalar malware, comum via e-mail, SMS (Smishing) ou chamadas (Vishing).
Dumpster Diving: Coleta de informações descartadas por empresas, onde atacantes podem encontrar dados sensíveis em documentos ou mídias removíveis.


    
- Sempre desconfie e leia novamente.
- Não baixe arquivos ou anexos de e-mails suspeitos.
- Não responda ou interaja com mensagens de texto suspeitas.
- Valide os links e o remetente dos e-mails.
- Descarte corretamente documentos e equipamentos.
- Pratique "mesa e tela limpa" ao bloquear a tela e deixar o ambiente de trabalho.
    

# Módulo 3 - Boas práticas e diretrizes

## **Compartilhamento de Acesso**

As credenciais de acesso identificam o usuário e autorizam o acesso a informações. As ações executadas com uma credencial são de responsabilidade do usuário e podem ser monitoradas. Proteja seu login e senha.
Alerta de clichê!
“Não compartilhamos escova de dentes, assim também devemos fazer com credenciais de acesso.”
Armazenamento
As informações devem ser guardadas em repositórios oficiais, garantindo segurança através de controles de proteção. Utilize os recursos da Udemy, OneDrive e SharePoint do seu respectivo iStudio para armazenar suas informações.

## **Softwares e malwares**

Softwares maliciosos e malwares são comuns em arquivos baixados da internet, exigindo cautela. O antivírus alerta sobre softwares não autorizados e recomenda consultar profissionais antes de instalar qualquer programa. É importante verificar a lista de softwares homologados.
Dica de Ouro: “Não assuma um risco sozinho, busque orientação.” Utilizar software não homologado pode gerar riscos desnecessários.
Senha Segura

## **As senhas são essenciais para o acesso aos sistemas da Compass e de seus clientes. Para garantir a segurança, siga estas recomendações:**

  - Evite informações pessoais como nomes, datas de aniversário e números de celular.
  - Crie senhas diferentes para cada conta.
  - Troque suas senhas regularmente.
  - Utilize um aplicativo de gerenciamento de senhas.
  - Sempre que possível, ative a autenticação de dois fatores (MFA).
  - Informe ao time de segurança sobre atividades suspeitas.
  - Use combinações de letras maiúsculas, minúsculas, números e caracteres especiais.

## **Uso da Internet**

**O acesso à internet e ao e-mail corporativo deve seguir as diretrizes de segurança e privacidade estabelecidas nas políticas da empresa. O uso de 
ferramentas de comunicação instantânea para assuntos profissionais é comum, mas deve-se evitar o uso para tratar de informações sensíveis e compartilhamento de arquivos.
    • Para compartilhar arquivos, utilize o armazenamento adequado.
    • Mantenha seu navegador atualizado.
    • O acesso a conteúdo ilícito é proibido por lei.
    • Evite a deep web, pois traz riscos de vazamento de informações e conteúdo ilegal.


## **MS Authenticator**

Aqui na Compass utilizamos para autenticação na plataforma Office365 o aplicativo Microsoft Authenticator. É preciso instalar em um dispositivo móvel para conseguir gerar o token de verificação.
A cada 14 dias, é solicitado um novo código para acessar os aplicativos que possuem o MFA. Com este código, o colaborador consegue entrar na sua conta do Microsoft 365.
Ao trocar de dispositivo móvel (celular/smartphone/tablet antigo), antes de desativar o cadastro do MFA no dispositivo antigo, é necessário ainda utilizá-lo para realizar o cadastro no novo dispositivo móvel.

## **Atualização de Software**

A atualização de software é essencial no mundo da tecnologia, onde buscamos sempre o melhor. É importante atualizar softwares e sistemas operacionais para garantir correções de vulnerabilidades, além de melhorar desempenho, compatibilidade e estabilidade. Isso ajuda a evitar interrupções e a aproveitar novos recursos.
Ao finalizar, mostre uma atitude proativa: clique em "Iniciar", use o botão direito do mouse e escolha "Atualizar e Reiniciar".

## **Incidentes de Segurança**

**Um incidente de segurança é um evento que pode afetar a disponibilidade, integridade e confidencialidade de informações, além de violar a Política de Segurança da Informação. Exemplos incluem:**

 • Instalação de ferramentas não autorizadas;
 • Presença de vírus e códigos maliciosos;
 • Tentativas de acesso não autorizadas;
 • Compartilhamento de credenciais.


## **Como relatar um incidente?**

Relatar um incidente é fundamental, pois permite que a equipe de InfoSec analise a situação e tome as medidas necessárias 
para corrigir e evitar recorrências. Se você identificar um incidente de segurança, relate-o imediatamente, podendo ser de 
forma identificada ou anônima. Links para mais informações estão disponíveis abaixo.

## **Redes Wi-fi**

Quem nunca procurou uma rede Wi-fi aberta quando atingiu o limite do plano de dados da sua operadora, que atire a primeira pedra.
Inúmeras vezes nos colocamos em risco nossas informações como senhas, históricos de navegação, e-mails, mensagens, dados e arquivos, simplesmente por utilizarmos um hotspot desconhecido, gratuito ou até mesmo com nomes muito convincentes ou semelhantes aos que costumamos usar.
É possível que alguém mal intencionado esteja bisbilhotando todos os pacotes que trafegam naquela rede aberta.


## **Em redes públicas:**

 - Evite redes abertas.
 - Use uma VPN confiável para proteger seus dados.
 - Desative a conexão automática a redes Wi-Fi públicas.
 - Desabilite o compartilhamento de arquivos e impressoras.
 - Não instale aplicativos que prometem quebrar senhas de redes Wi-Fi.

## **Em sua rede doméstica:**

 - Configure uma senha forte no roteador e troque-a periodicamente, utilizando os padrões WPA2 ou WPA3.
 - Mantenha o firmware do roteador atualizado, preferindo a atualização automática.
 - Altere os padrões de fábrica, como o nome da rede (SSID) e as credenciais de administrador.
 - Desative o acesso remoto ao roteador.
 - Ao inserir informações confidenciais em sites, verifique se utilizam conexões seguras (https).


# Módulo 4 - Segurança em IA Generativa

O que é IA Generativa?
A Inteligência Artificial generativa é um ramo da IA focado na criação de novos conteúdos, como texto, 
imagens, vídeos, música e código, a partir de dados existentes. Os algoritmos de IA aprendem com os dados
fornecidos e conseguem gerar saídas semelhantes, mas não idênticas, com base no conhecimento adquirido durante o treinamento.

## **Ambiente e utilização de ferramentas IA**

Há diversas ferramentas gratuitas e pagas, antes de iniciar um trabalho usando-as, leia e analise todos os itens do contrato ou termo de uso.
Saber como os dados inseridos serão usados é imprescindível para a segurança dessas informações. 
Você poderá involuntariamente autorizar ouso ou deixar os dados disponíveis para terceiros.
Utilize ferramentas homologadas e licenças comerciais em ambiente corporativo, e isso não significa você mesmo comprar uma licença.
É proibido o uso dessas ferramentas para uso pessoal, atividades ilegais, fraudulentas, danos físicos e econômicos, violação de 
privacidade ou que contrariem a política de segurança da informação.




## **Como proteger os dados e informações**

Quando buscar apoio de uma IA generativa para melhorar ou agilizar seu trabalho, é vital lembrar de proteger as informações de clientes ou da empresa que esteja trabalhando.

**Cuide com inteligência! Aqui vão algumas dicas:**

- Remova dados pessoais, senhas ou tokens das consultas que enviar, independente que sejam dados de ambientes de desenvolvimento ou de produção.
- Quando possível utilize mascaramento de dados.
- Troque nas consultas qualquer dado real de clientes ou da empresa, como nomes próprios das empresas, comentários de código, casos reais.

## **Controles mínimos de segurança**

As ferramentas de IA devem seguir requisitos mínimos de segurança, incluindo gestão de acessos, monitoramento, documentação e capacitação. É importante realizar análise de riscos, usar o Jira para solicitações de acesso, documentar procedimentos no SharePoint ou Confluence, e participar de treinamentos obrigatórios.




       
