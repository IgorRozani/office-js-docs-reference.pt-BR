# <a name="contribute-to-this-documentation"></a>Contribuir para esta documentação

Agradecemos seu interesse em nossa documentação!

* [Maneiras de contribuir](#ways-to-contribute)
* [Contribuir usando o GitHub](#contribute-using-github)
* [Contribuir usando o Git](#contribute-using-git)
* [Como usar o Markdown para formatar seu tópico](#how-to-use-markdown-to-format-your-topic)
* [Perguntas frequentes](#faq)
* [Mais recursos](#more-resources)

## <a name="ways-to-contribute"></a>Maneiras de contribuir

Veja a seguir algumas maneiras de contribuir com esta documentação:

* Para fazer pequenas alterações em um artigo [contribua usando o GitHub](#contribute-using-github).
* Para fazer grandes alterações ou alterações que envolvam códigos, [contribua usando o Git](#contribute-using-git).
* Documentação de relatar bugs via GitHub problemas.
* Solicitar nova documentação no site [UserVoice de Plataforma do Desenvolvedor do Office](http://officespdev.uservoice.com)

## <a name="contribute-using-github"></a>Contribuir usando o GitHub

Use o GitHub para contribuir com esta documentação sem precisar clonar o repositório em sua área de trabalho. Essa é a maneira mais fácil de criar uma solicitação pull neste repositório. Use este método para fazer uma pequena alteração que não envolva alterações de código. 

**Observação** Usar este método permite contribuir em um artigo de cada vez.

### <a name="to-contribute-using-github"></a>Para contribuir usando GitHub

1. Encontre o artigo que você deseja que contribuem para no GitHub.
2. Quando estiver no artigo no GitHub, acesse o GitHub (obtenha uma conta gratuita na página [Join GitHub](https://github.com/join)).
3. Escolha o **ícone de lápis** (editar o arquivo em sua bifurcação deste projeto) e faça suas alterações na janela **<> Edit fie**. 
4. Role até a parte inferior e insira a descrição.
5. Escolha a opção para propor a alteração e criar a solicitação pull em **Propose file change**>**Create pull request**.

Assim, você envia com êxito uma solicitação pull. As solicitações pull geralmente são analisadas dentro de 10 dias úteis. 


## <a name="contribute-using-git"></a>Contribuir usando o Git

Use o Git para fazer alterações substanciais, tais como:

* Contribuir com códigos.
* Contribuir com alterações que afetam o significado.
* Contribuir com grandes alterações de texto.
* Adicionar novos tópicos.

### <a name="to-contribute-using-git"></a>Para contribuir usando gito

1. Se você não tiver uma conta, configure uma no [GitHub](https://github.com/join). 
2. Depois que tiver a conta, instale o Git em seu computador. Siga as etapas no tutorial [Configurar gito] .
3. Para enviar uma solicitação pull usando o Git, siga as etapas da seção [Usar o GitHub, o Git e este repositório](#use-github-git-and-this-repository).
4. Será solicitado que você assine o Contrato de licença do colaborador se você for:

    * um membro do grupo Microsoft Open Technologies; 
    * um colaborador que não trabalha na Microsoft.

Como membro da comunidade, você deve assinar o Contrato de Licença de Contribuição (CLA) antes de poder contribuir com envios volumosos para um projeto. Você só precisa completar e enviar a documentação uma vez. Reveja cuidadosamente o documento. Talvez seja necessário que seu empregador assine o documento.

Assinar o CLA não concede a você direitos para comprometer para o repositório principal, mas isso significa que as equipes de desenvolvedor do Office e Office Developer publicação de conteúdo será capazes de revisar e aprovar suas contribuições. Você está creditado para seus envios.

As solicitações pull geralmente são analisadas dentro de 10 dias úteis.

## <a name="use-github-git-and-this-repository"></a>Use o GitHub, o Git e este repositório

**Observação:** a maior parte das informações desta seção pode ser encontrada nos artigos da [Ajuda do GitHub].  Se você estiver familiarizado com o Git e o GitHub, pule para a seção **Contribuir e editar conteúdo** para ver as informações específicas sobre o fluxo de código/conteúdo desse repositório.

### <a name="to-set-up-your-fork-of-the-repository"></a>Configurar sua bifurcação do repositório

1.  Configure uma conta GitHub para que você pode contribuir para esse projeto. Caso ainda não tenha feito isso, acesse o [GitHub](https://github.com/join) e faça isso agora.
2.  Instale o Git em seu computador. Siga as etapas no tutorial [Configurar gito] .
3.  Crie sua própria bifurcação para este repositório. Para fazer isso, na parte superior da página, escolha o botão de **bifurcação** .
4.  Copie sua bifurcação para seu computador. Para fazer isso, abra o Git Bash. No prompt de comando, digite:

        git clone https://github.com/<your user name>/<repo name>.git

    Em seguida, crie uma referência para o repositório raiz inserindo esses comandos:

        cd <repo name>
        git remote add upstream https://github.com/OfficeDev/<repo name>.git
        git fetch upstream

Parabéns! Agora seu repositório está configurado. Você não precisará repetir essas etapas novamente.

### <a name="contribute-and-edit-content"></a>Contribuir e editar o conteúdo

Para que o processo de contribuição seja o mais contínuo possível, siga estas etapas.

#### <a name="to-contribute-and-edit-content"></a>Para contribuir e editar conteúdo

1. Crie uma nova ramificação.
2. Adicione novo conteúdo ou edite o conteúdo existente.
3. Envie uma solicitação pull para o repositório principal.
4. Exclua a ramificação.

**Importante**: limite cada ramificação a um único conceito/artigo para simplificar o fluxo de trabalho e reduzir a chance de conflitos de mesclagem. O conteúdo apropriado para uma nova ramificação inclui:

* Um novo artigo.
* edições de ortografia e gramática; e
* aplicar uma única alteração de formatação em um grande conjunto de artigos (por exemplo, aplicar um novo rodapé sobre direito autoral).

#### <a name="to-create-a-new-branch"></a>Para criar uma nova ramificação

1.  Abra gito Bash.
2.  No prompt de comando do Git Bash, digite: `git pull upstream master:<new branch name>`. Isso cria uma nova ramificação local copiada da última ramificação-mestra do OfficeDev.
3.  No prompt de comando do Git Bash, digite: `git push origin <new branch name>`. Isso alertará o GitHub para a nova ramificação. Agora você deverá surgir a nova ramificação na sua bifurcação do repositório no GitHub.
4.  No prompt de comando do Git Bash, digite `git checkout <new branch name>` para alternar para a nova ramificação.

#### <a name="add-new-content-or-edit-existing-content"></a>Adicionar novo conteúdo ou editar o conteúdo existente

Navegue até o repositório em seu computador usando o Explorador de Arquivos. Os arquivos do repositório estarão em `C:\Users\<yourusername>\<repo name>`.

Para editar arquivos, abra-os em um editor de sua escolha e modifique-os. Para criar um novo arquivo, use o editor de sua escolha e salve o novo arquivo no local apropriado em sua cópia local do repositório. Enquanto estiver trabalhando, salve seu trabalho com frequência.

Os arquivos localizados no `C:\Users\<yourusername>\<repo name>` são uma cópia de trabalho da ramificação nova que você criou em seu repositório local. Qualquer que seja a alteração você faça nessa pasta, ela só afetará o repositório local quando você confirmar uma alteração. Para confirmar uma alteração no repositório local, digite os seguintes comandos no GitBash:

    git add .
    git commit -v -a -m "<Describe the changes made in this commit>"

O comando `add` adiciona suas alterações para uma área de preparo em preparação para confirmá-las no repositório. O período posterior ao comando `add` especifica que você deseja preparar todos os arquivos adicionados ou modificados, verificando repetidamente as subpastas. (Caso você não queira confirmar todas as alterações, é possível adicionar arquivos específicos. Você também pode desfazer uma confirmação. Para ajuda, digite `git add -help` ou `git status`.)

O comando `commit` aplica as alterações preparadas ao repositório. A opção `-m` significa que você está fornecendo o comentário de confirmação na linha de comando. As opções -v e -a podem ser omitidas. A opção -v corresponde à saída detalhada do comando e a opção -a faz o que você já fez com o comando adicionar.

Você pode confirmar várias vezes enquanto estiver fazendo seu trabalho ou apenas uma vez quando terminar.

#### <a name="submit-a-pull-request-to-the-main-repository"></a>Enviar uma solicitação pull para o repositório principal.

Quando terminar o trabalho e estiver pronto para mesclá-lo no repositório principal, siga estas etapas.

#### <a name="to-submit-a-pull-request-to-the-main-repository"></a>Para enviar uma solicitação pull para o repositório principal

1.  No prompt de comando do Git Bash, digite: `git push origin <new branch name>`. Em seu repositório local, `origin` refere-se ao repositório do GitHub a partir do qual você clonou o repositório local. Esse comando coloca o estado atual do sua nova ramificação, incluindo todas as confirmações feitas nas etapas anteriores, na ramificação do GitHub.
2.  No site do GitHub, navegue em sua bifurcação para a nova ramificação.
3.  Escolha o botão **Pull Request** na parte superior da página.
4.  Verifique se o branch Base é `OfficeDev/<repo name>@master` e o branch Head é `<your username>/<repo name>@<branch name>`.
5.  Escolha o botão para atualiza o intervalo de confirmação **Update Commit Range**.
6.  Inclua um título à sua solicitação pull e descreva todas as alterações que você estiver fazendo.
7.  Envie a solicitação pull.

Um dos administradores do site processará sua solicitação pull. Sua solicitação pull ficará visível no site OfficeDevOfficeDev/<repo name> em Problemas. Quando a solicitação pull for aceita, o problema será resolvido.

#### <a name="create-a-new-branch-after-merge"></a>Criar uma nova ramificação após a mesclagem

Depois que uma ramificação for mesclada com sucesso (ou seja, sua solicitação for aceita), não continue a trabalhar na ramificação local. Isso poderá gerar conflitos de mesclagem caso você envie outra solicitação pull. Para fazer uma nova atualização, crie uma nova ramificação local com base na ramificação de upstream mesclada com êxito e, então, exclua a ramificação local inicial.

Por exemplo, se sua ramificação local X foi mesclada com êxito na ramificação-mestra OfficeDev/microsoft-graph-docs e você quer fazer atualizações adicionais no conteúdo mesclado. Crie uma nova ramificação local, X2, da ramificação-mestra OfficeDev/microsoft-graph-docs. Para fazer isso, abra o GitBash e execute os seguintes comandos:

    cd microsoft-graph-docs
    git pull upstream master:X2
    git push origin X2

Agora você tem cópias locais (em uma nova ramificação local) do trabalho que enviou na ramificação X. A ramificação X2 também contém todo o trabalho que outros autores mesclaram, portanto, se seu trabalho depender do trabalho de outras pessoas (por exemplo, imagens compartilhadas), ele estará disponível em nova ramificação. Você pode confirmar se seu trabalho anterior (e o trabalho de outras pessoas) está na ramificação verificando a nova ramificação...

    git checkout X2

... e verificando o conteúdo. (O comando `checkout` atualiza os arquivos no `C:\Users\<yourusername>\microsoft-graph-docs` para o estado atual da ramificação do X2.) Assim que você verificar a nova ramificação, será possível fazer atualizações no conteúdo e confirmá-las como de costume. No entanto, para evitar trabalhar na ramificação mesclada (X) por engano, o melhor a fazer será excluí-la (confira a seguinte seção: **Excluir uma ramificação**).

#### <a name="delete-a-branch"></a>Excluir uma ramificação

Depois que as alterações forem mescladas com êxito no repositório principal, exclua a ramificação utilizada, pois você não precisará mais dela.  Qualquer trabalho adicional deve ser feito em uma nova ramificação.  

#### <a name="to-delete-a-branch"></a>Para excluir uma ramificação

1.  No prompt de comando do Git Bash, digite: `git checkout master`. Isso garante que você não fique na ramificação a ser excluída (o que não é permitido).
2.  Em seguida, no prompt de comando, digite `git branch -d <branch name>`. Esse comando exclui a ramificação em seu computador somente se ela tiver sido mesclada com êxito no repositório upstream. (Você pode superar esse comportamento com o sinalizador `–D`, mas primeiro certifique-se de que você deseja fazer isso.)
3.  Por fim, digite `git push origin :<branch name>` no comando prompt (um espaço antes dos dois pontos e nenhum espaço depois deles).   Essa ação excluirá a ramificação em uma bifurcação do github.  

Parabéns, você contribuiu com êxito para o projeto.

## <a name="how-to-use-markdown-to-format-your-topic"></a>Como usar o Markdown para formatar seu tópico

### <a name="markdown"></a>Markdown

Todos os artigos neste repositório usam Markdown. Uma introdução completa (e lista de todos os a sintaxe) podem ser encontradas no [Daring Fireball - redução].
 
## <a name="faq"></a>Perguntas frequentes

### <a name="how-do-i-get-a-github-account"></a>Como posso obter uma conta GitHub?

Preencha o formulário em [Ingressar no GitHub](https://github.com/join) para abrir uma conta gratuita do GitHub. 

### <a name="where-do-i-get-a-contributors-license-agreement"></a>Onde posso obter um Contrato de Licença do Colaborador? 

Um aviso será automaticamente enviado para você informando que é preciso assinar o CLA (Contrato de Licença do Colaborador) se sua solicitação de recebimento exigir um. 

Como membro da comunidade, **você deve assinar o CLA (Contrato de Licença do Colaborador) antes de poder contribuir com envios volumosos para esse projeto**. Você só precisa concluir e enviar a documentação uma vez. Reveja cuidadosamente o documento. Talvez seja necessário que seu empregador assine o documento.

### <a name="what-happens-with-my-contributions"></a>O que acontece com as minhas contribuições?

Quando você envia suas alterações, por meio de uma solicitação pull, nossa equipe será notificada e a examinará. Você receberá notificações sobre sua solicitação pul do GitHub. Além disso, você também poderá ser notificado por uma pessoa de nossa equipe se precisarmos de mais informações. Se a solicitação de recepção for aprovada, atualizaremos a documentação. Reservamo-nos o direito de editar seu envio por motivos legais, estilísticos, de clareza ou por outros problemas.

### <a name="can-i-become-an-approver-for-this-repositorys-github-pull-requests"></a>Posso me tornar um aprovador de solicitações pull desse repositório do GitHub?

Atualmente, não estamos autorizando que colaboradores externos aprovem solicitações pull neste repositório.

### <a name="how-soon-will-i-get-a-response-about-my-change-request"></a>Em quanto tempo terei uma resposta sobre a solicitação de alteração?

As solicitações pull geralmente são analisadas dentro de 10 dias úteis.


## <a name="more-resources"></a>Mais recursos

* Para saber mais sobre redução, vá para o site do criador redução [Daring Fireball].
* Para saber mais sobre como usar gito e GitHub, confira-a [ajuda do GitHub].

[GitHub Home]: http://github.com
[Ajuda do GitHub]: http://help.github.com/
[Configurar gito]: https://help.github.com/articles/set-up-git/
[Daring Fireball - redução]: http://daringfireball.net/projects/markdown/
[Daring Fireball]: http://daringfireball.net/
