# Como usar o `GitHub`?

Oi!
<br> Somos alunos da primeira turma da Ilum e viemos introduzir o `GitHub` para você!
<br> Vamos pelo "básico"... o que é `GitHub`?
<br> Esse site que você está inserido agora pertence a uma plataforma, o `GitHub`. Aqui há a hospedagem e o controle de distintos códigos. Além de postar códigos e mais códigos, você pode colaborar e trocar informações com outros criadores.
<br> Mas por que tudo isso é possível?
<br> O `GitHub` faz parte do Git, um projeto que realiza manutenções de *software* nas suas diversas versões de criação. Isto é, ao invés de conter somente uma cópia de todo o histórico de formação, o sistema armazena todo o repertório de alterações. Isso será importante! 👀 
<br>
<br> Bom, primeiramente, você deve instalar o `Github` em seu computador, para que seja possível realizar seus projetos. A seguir te apresentaremos o passo-a-passo para instalação em Windows!
<br> Passo 1: entre no [site](https://desktop.github.com/).
<br> Passo 2: clique em **Download for Windows (64bit)**.
<br> Passo 3: nos arquivos do seu computador, entre em **Dowloads** e clique 2x em **GithubDesktopSetup**. 
<br> Assim, após a instalação ser concluída, o `GitHub Desktop` estará disponível para sua utilização. 🥳
<br>
<br> Antes de tudo, veremos alguns apetrechos: o `GitHub` usa distintas ferramentas e vamos explicá-las sucintamente para você. 
<br> Os `Repositories` são locais onde os arquivos dos seus projetos serão armazenados. 
<br> O `Commit`é uma unidade estrutural com um cronograma de projeto Git. Nele ficarão armazenadas todas as informações essenciais da formação e da estruturação do seu projeto, capturando, então, sempre o estado do seu trabalho. 
<br> O `.gitignore` realiza a seleção de arquivos e/ou pastas que serão ignorados na criação de um novo repositório. Saiba mais [aqui](https://docs.github.com/pt/get-started/getting-started-with-git/ignoring-files).
<br> O `README` é basicamente um local em que pode ser escrito um texto, como esse texto que você está lendo! Ele geralmente aparece no início de um repositório e contém informações importantes para os usuários que o acessarem. 
<br> Por fim, o `fork` é um comando, o qual copia o repositório de uma outra pessoa, podendo, então, alterá-lo da forma que você quiser! 
<br> Agora vamos iniciar o tutorial do uso do GitHub. 😎
<br>
## Criando uma conta... 📚
<br> Estando na [página inicial](https://github.com/), você clicará em **Sign up** no canto superior direito. O site pedirá, então, um e-mail. É recomendado que você dê àquele que é associado à faculdade, para ser possível solicitar requintes acadêmicos.
<br> Após isso, também coloque uma senha. Lembre-se que senhas são individuais!
<br> Já estamos terminando... coloque um nome de usuário. Inclusive, prazer, somos Barbarailum, gustavercosa, VictorPuntelRui e viyuetuki.
<br> Por fim, aprove a inscrição! Tecle "y" e envie.
<br>
## Iniciando as criações... 📎
<br> Vamos gerar um repositório! Ao clicar no seu respectivo ícone, selecione a aba **Your profile**, você será direcionado para a página de usuário. Lá, acesse os repositórios em **Repositories**.
<br> Para criar é simples. Clique em **New**, no canto superior direito e o personalize: coloque qualquer nome no espaço destinado, o **Repository name**. Se quiser, também pode especificá-lo adicionando um comentário em **Description**.
<br> Em seguida, selecione o tipo: público ou privado. Para fins acadêmicos, é recomendado usar o estilo **Public**, pois você compartilhará informações com outras pessoas.
<br> Por fim, "enfeite" seu repertório: você quer um arquivo `README`? Quais arquivos você quer ignorar com o `.gitignore`? Qual licença você usará? Essa última seleção é delicada! A licença é o que determina como e se ocorrerá o compartilhamento legal de informações contidas no `GitHub`. Cada uma atua de uma forma diferente, então, estude-as! Saiba mais [aqui](https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).
<br> Pronto, você pode terminar de estruturar seu repertório clicando em **Create repository**.

## Aprendendo comandos para conexão entre aplicativo do `GitHub` e `GitHub Web`... 💻 
<br> Antes de fazermos um passo-a-passo e te ensinarmos como fazer essa conexão entre `GitHub offline` e `GitHub Web`, vamos te mostrar uma prévia do que cada comando faz em forma de tópicos.
<br> Para poder fazer isso, você deve criar uma pasta em seu computador e, após adentrá-la, precisa clicar com o botão direito do mouse e selecionar **Git Bash Here**. Com isso, será aberta uma janela/*interface* que é o terminal do Git (famosa tela preta), no qual é utilizada a linguagem Bash. 
<br> Assim, vamos para alguns comandos que você pode utilizar nesse terminal em um primeiro momento:
- `git clone` link: este comando copia os arquivos do `GitHub` para uma pasta em seu computador. Para utilizá-lo basta apenas digitar "git clone" e ao lado colocar o link do seu repositório. Esse link vai estar disponível no canto superior direito, em um “botão” escrito **Code**, em verde. Basta copiá-lo e colar no terminal, para isso o `Ctrl+V` não funciona, é preciso ou colocar usando o botão direito do mouse e **Paste** ou clicando nas teclas `Shift` e `Insert` do teclado. Exemplo da estrutura: git clone https://github.com/VictorPuntelRui/PCD.git;
- `cd` pasta: utilizamos esse código para entrar em uma pasta específica, podendo ela, por exemplo, representar o repositório. Para usá-lo, digite "cd" e ao lado escreva a pasta que você quer acessar. Exemplo: cd tutorial_GitHub;
<br> Observação: caso você não queira entrar desse modo, após clonar seu repositório do `GitHub Web` em seu computador, feche a *interface*, abra a pasta manualmente, já dentro dela, clique de novo com o botão direito em um local vazio e selecione **Git Bash Here**, assim, será aberta o terminal mais uma vez e você o estará usando já dentro da pasta aberta.
- `git status`: usando desse comando, podemos pedir para que seja mostrado o *branch* em que se está atualmente, os arquivos adicionados ou alterados no computador que não foram enviados ao `GitHub Web`, e se foi dado `commit` em algum arquivo (caso não, avisa se há arquivos a serem adicionados). Vale ressaltar que, se teve modificações em arquivos que ainda precisam passar pelo comando `commit`, esses arquivos serão mostrados em vermelho e, logo após o `commit` (não se preocupe, te ensinaremos em um dos tópicos posteriores), se “git status” for usado novamente, o nome do que se alterou passa a estar em verde;
<br> Observação: caso você tenha lido atentamente, terá percebido que usamos a palavra *branch* e, provavelmente, deve estar se perguntando o que ela significa. Assim, pode-se dizer que *branch* é o ramo, ou seja, você pode estar no ramo principal (*main*) ou em um outro que você criou como uma cópia do primeiro. Esse criado por você é uma maneira de editar os arquivos sem alterar os originais, então, basicamente, é criada uma cópia de tudo o que você tem no seu repositório, por exemplo, como um "universo paralelo", no qual você realiza as alterações que quiser, sem alterar o do ramo original, e, após isso, pode fundi-lo com o arquivo do *main*. Isso é muito útil quando você tem um código no *main* já divulgado, com usuários, todavia você quer fazer modificações ou melhorias sem risco de estragar algo que havia feito anteriormente e de prejudicar quem está usando-o no momento, assim, criando um “universo paralelo”, você pode alterar o que quiser e depois fundir (dar *merge*) com o principal e tudo estará atualizado, podendo os usuários utilizar a nova versão. Para criar um *branch* novo, basta ir em **main** no canto superior esquerdo no `GitHub Web`, logo abaixo da barra de opções da parte de cima, e escrever o nome que ser dar a ele e, com isso, aparecerá a opção **Create branch**. Como não foi dito antes, para navegar entre eles, é nesse mesmo local que aparecerão seus `branchs` criados e você pode selecioná-los para ir mudando.
- `git add .` ou `git add` "arquivo": após você ter visto com o `git status` se tinha alterações nos seus arquivos, caso tenha, conforme dito, elas vão ser mostradas em vermelho. Para adicioná-las e ser possível dar o `commit` para, assim, poder enviá-las ao `GitHub Web`, você deve usar o comando “git add” e, ao lado ou usar “.” ou colocar o nome do seu arquivo alterado. A diferença é que, com o ponto, todas as mudanças feitas em todos os arquivos vão ficar disponíveis para dar o `commit` e serem enviadas para o `GitHub Web` (ficando verde no `git status`), enquanto, colocando só o nome do arquivo em específico, só as alterações dele serão atualizadas no `git status`. Exemplos de estrutura: “git add . ”  ou “git add arquivo_alterado”. Sendo “arquivo_alterado” o nome de um arquivo.
- `git commit -m` "descrição”: bem como já foi dito na parte sobre `GitHub Web`, sabemos que o “SALVAR” do GitHub é o `commit`, assim, para fazer as atualizações no *offline* não é diferente. Logo, esse comando serve para, após você ter modificado algo, quando quiser salvar para depois enviar ao `GitHub Web`, deve dar `commit` para ser possível. Além disso, cabe ressaltar que aqui também é necessário colocar uma descrição para suas alterações (e vamos combinar, por mais que pareça chato no começo ficar fazendo essas descrições a cada commit, você vai se agradecer no futuro, pois isso facilita muito a vida quando queremos viajar no tempo e olhar nosso histórico de edições);
- `git push`: como a própria tradução sugere, esse comando “empurra” suas alterações e tudo o que você fez pelo `GitHub` *offline* para o *online*;
- `git pull`: esse outro comando também segue a mesma ideia da sua tradução e realiza a função contrária do `git push`, esse, ao contrário daquele, “puxa” o que foi feito no `GitHub Web` para os seus arquivos salvos no computador;
- `git checkout` "branch": usamos desse comando para entrar em um *branch* específico, em outras palavras, trocar de "universo paralelo" e transitar entre eles. Ao escrever "git chechout" e, ao lado, indicar para qual *branch* você quer ir, você será direcionado para tal. Exemplo: git checkout universo2. Nesse caso universo2 é um *branch* criado do repositório. Uma observação é que o *branch* pode ser tanto o *main* quanto outros criados por você (derivados do *main*). 
<br> E, assim, finalizamos os comandos principais que usamos no terminal do Git que você deve saber para fazer a comunicação entre o computador e o `GitHub Web`! 😁

## Acabou?
Você se deve estar se perguntando: “Ok, acho que consegui aprender o que cada um faz basicamente, mas e agora? O que eu faço?”. Essencialmente, já sabendo as funções de cada um você deve ir usando-os em seu devido momento, de acordo com o que você quer fazer. Mas, para te dar uma orientação e não te deixar perdido (aqui ninguém larga a mão de ninguém, estamos todos no mesmo barco), vamos passar uma sequência deles para um exemplo de tarefa e você pode o tomar como base para realizar o que quiser.
Logo, pensando em uma situação em que já temos uma conta no `GitHub`, já criamos um repositório, criamos nossos arquivos e agora queremos editá-los a partir do computador, podemos seguir o seguinte passo-a-passo:
- Criar uma pasta chamada "GitHub";
- Entrar nela e clicar com o botão direito e selecionar **Git Bash Here**;
- Ir no `GitHub Web`, copiar o link do repositório, que se encontra no botão **Code**, e dar o comando: `git clone` link;
- Para entrar em uma pasta chamada "aula_github", dar o comando: `cd` aula_github;
- Para verificar se está tudo certo, dar o comando: `git status`;
- Alterar o que quisermos nos arquivos importados para a pasta;
- Dar o comando: `git status`;
- Para adicionar as alterações feitas, dar o comando: `git add .`;
- A fim de se verificar que foi adicionado, dar: `git status`;
- Com tudo certo, da `commit` e adicionar descrição da seguinte maneira: `git commit -m` “adicionei introdução no arquivo texto_ILUM.txt”;
- Verificando se há algo a mais para dar commit, dar: `git status`;
- Para enviar tudo ao `GitHub Web`, dar: `git push`.
<br> E esse foi o nosso tutorial! Esperamos ter ajudado e ter te dado uma luz no fundo do túnel. 
<br> Além disso, um adicional seria, caso, logo após, nós editamos algo pelo `GitHub Web` e queremos trazer para o computador, devemos dar: `git pull`. Caso tivéssemos um ramo chamado "ramo_1" e quiséssemos mudar do *main* para ele, deveríamos dar: `git checkout` ramo_1. Para conferir se realmente mudamos: `git status`. Se, após feito tudo de desejado, quiséssemos voltar ao ramo principal: `git checkout` main.
<br> Com isso, explicamos tudo o que você pode fazer com os comandos, basta usar esses aprendizados e fazer o que deseja!
<br> Esperamos muito ter ajudado e contribuído para o seu aprendizado! Use e abuse do `GitHub`, ele é uma plataforma muito útil e importante! ✨
