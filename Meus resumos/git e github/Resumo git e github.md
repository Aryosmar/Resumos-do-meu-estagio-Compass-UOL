# **Git e Github**
Git é um sistema de controle de versão distribuído, usado para gerenciar o desenvolvimento de projetos de software. Ele permite que vários desenvolvedores trabalhem em um mesmo projeto de forma colaborativa, rastreando as alterações no código, armazenando diferentes versões e facilitando o trabalho em equipe. 
### **Github** 
É um serviço de hospedagem, é um serviço na cloud, como todos dizem.
### **Configurando o git:**
Digite o comando **git config –global user.name “Aryosmar”**

Digite o comando **git config –global user.email andre@andreiacono.com**

Digite o comando **git config –global init.default branch main**

### **O que untracked**
No Git, o termo **untracked** (não rastreado) se refere a arquivos que existem no seu diretório de trabalho, mas que o Git ainda não está monitorando. Ou seja, esses arquivos **não foram adicionados ao controle de versão**.
### **O que é tracked**
No Git, um arquivo tracked (rastreados) são aqueles que o Git está monitorando ativamente para mudanças. Ou seja, esses arquivos já foram adicionados ao repositório e fazem parte do controle de versão. O Git rastreia esses arquivos para detectar modificações e incluí-los em futuros commits.
### **O que é working (Diretório de Trabalho)**
É o espaço onde você faz alterações nos arquivos do seu projeto. Ele contém todos os arquivos e diretórios que você está desenvolvendo ativamente.
### **O que é staging Area (Área de Preparação)**
É uma área intermediária onde você prepara os arquivos antes de fazer um commit. Os arquivos que estão na staging area são aqueles que você selecionou para incluir no próximo commit.

### **O git reset e seus tipos:**

**git reset –soft  <commit>**

**O que faz:** Move o **HEAD** para o **commit** especificado, mas mantém as alterações na staging area.

**git reset –mixed <commit>**

**O que faz**: Move o **HEAD** para o **commit** especificado e remove as alterações da staging area, mas mantém as alterações no diretório de trabalho.

**git reset –hard <commit>** Move o **HEAD** para o **commit** especificado, desfaz as alterações na staging area e no diretório de trabalho.

**Uso típico:** Use com cuidado, pois isso apaga permanentemente todas as alterações desde o commit especificado. É útil quando você quer reverter completamente o repositório a um estado anterior.

### **O que é uma branch:**

Uma branch (ou ramificação) no Git é uma linha de desenvolvimento independente que permite que você trabalhe em novas funcionalidades, correções de bugs ou experimentos sem afetar a versão principal do seu projeto. As branches são uma das principais características do Git e ajudam a gerenciar diferentes versões de um código.

### **Resumo do Fluxo:**
     
- **Início:** Você tem a branch main com a versão estável do seu aplicativo.
- **Desenvolvimento:** Cria branches feature-login e bugfix-header para trabalhar em novas funcionalidades e correções de bugs.
 - **Integração:** Mescla as alterações das branches de volta à main quando estiverem prontas.
- **Limpeza:** Remove branches que não são mais necessárias.

### **Vantagens desse Fluxo:**
- Isolamento: Você pode trabalhar em múltiplas funcionalidades e correções simultaneamente sem interferir na versão estável do aplicativo.
- Colaboração: Outros desenvolvedores podem fazer o mesmo, criando suas próprias branches para diferentes tarefas.
- Histórico Limpo: O histórico de commits se mantém organizado, facilitando a revisão de mudanças e a identificação de problemas.

### Comandos do Git:
**Git add index.html** é usado para adicionar um determinado arquivo(**nesse caso o index.html**) ao staging area(área de preparação)  no git.sso significa que o Git está preparado para incluir este arquivo no próximo commit.

**git add .** adiciona todos os arquivos modificados, novos e rastreados ao staging.

**git commit -m** é usado para criar um commit no Git com uma mensagem de commit fornecida diretamente na linha de comando.

**git diff** é utilizado no Git para mostrar as diferenças entre o conteúdo de arquivos em diferentes estados. Ele compara as mudanças feitas no diretório de trabalho em relação à versão anterior, mostrando as linhas que foram adicionadas, modificadas ou removidas.

**git log** é utilizado para visualizar o histórico de commits do seu repositório Git. Ele exibe uma lista dos commits feitos, incluindo informações importantes sobre cada um deles.

**git log –oneline** é uma maneira simplificada de visualizar o histórico de commits em um repositório Git. Ele exibe uma lista compacta, mostrando apenas o hash curto do commit e a mensagem de commit em uma única linha para cada entrada.

**git rm** é usado para remover arquivos do seu repositório Git, tanto do diretório de trabalho quanto da staging area. Ao executar esse comando, você está dizendo ao Git para excluir um arquivo e preparar essa exclusão para o próximo commit.

**git restore –staged <arquivo>** é usado para remover arquivos da staging area (área de preparação) e reverter seu estado para o último commit. Isso é útil se você adicionou um arquivo à staging area usando git add, mas depois decidiu que não deseja incluir essas alterações no próximo commit

**git restore<arquivo>** é usado para restaurar um arquivo específico no seu diretório de trabalho para o estado do último commit. Isso significa que ele desfaz quaisquer alterações não commitadas feitas nesse arquivo, retornando-o ao que estava no último snapshot (commit).

**git mv<nome do arquvo> <novo nome>** é usado para renomear ou mover arquivos dentro de um repositório Git.

**git commit -m “mensagem” –amend** é usado para modificar o último commit que você fez. Ele permite que você adicione novas alterações ao commit mais recente ou altere a mensagem desse commit.

**git log  -p** é uma ferramenta poderosa para desenvolvedores que desejam ter uma visão detalhada do histórico de commits e das alterações feitas no código, ajudando a entender a evolução do projeto e a investigar problemas de forma mais eficaz.

**git branch** Para listar todas as branches no repositório, você pode simplesmente usar.

**git branch <nome da branch>**  Para criar uma nova branch.

**git switch <nome do arquivo>** é usado para mudar entre branches no Git.

**git merge -m “mensagem” <nome da brange>** O comando git merge é usado para integrar mudanças de uma branch (ou ramificação) em outra. No entanto, a opção -m para especificar uma mensagem de merge é um pouco diferente do que você pode estar pensando.

**git branch -d <nome da branch>** é utilizado para deletar uma branch local em um repositório Git. Essa operação é útil para limpar branches que não são mais necessárias após a mesclagem ou finalização do trabalho.

**git push  --all** é utilizado para enviar todas as branches locais para um repositório remoto. Isso é útil quando você deseja garantir que todas as suas branches locais sejam atualizadas no repositório remoto sem precisar especificar cada uma delas individualmente.

**git pull** é utilizado para atualizar sua branch local com as alterações mais recentes do repositório remoto. Ele é uma combinação de dois comandos git fetch(que baixa as alterações do remoto) e git merge (que mescla essas alterações na sua branch atual). 

