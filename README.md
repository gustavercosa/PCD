# Atividade do GitHub

Oi! 👋 
<br> Somos alunos da primeira turma da Ilum e viemos introduzir o `GitHub` para vocês!
<br> Vamos pelo "básico"... o que é `GitHub`?
<br> Esse site que você está inserido agora pertence a uma plataforma, o `GitHub`. Aqui há a hospedagem e o controle de distintos códigos, como esse texto que vocês estão lendo! Além de postar códigos e mais códigos, vocês podem colaborar e trocar informações com outros criadores.
<br> Mas por que tudo isso é possível?
<br> O `GitHub` faz parte do Git, um projeto que realiza manutenções de software nas suas diversas versões de criação. Isto é, ao invés de conter somente uma cópia de todo o histórico de formação, o sistema armazena todo o repertório de alterações. Isso será importante futuramente! 👀 
<br>
<br> Agora vamos iniciar o tutorial.
<br>
<br> Criando uma conta...
<br> Estando na página inicial (https://github.com/), vocês clicarão em "Sign up" no canto superior direito. O site pedirá, então, um e-mail. É recomendado que vocês deem àquele que é associado à faculdade, para ser possível solicitar requintes acadêmicos.
<br> Após isso, também coloquem uma senha. Lembrem-se que senhas são individuais!
<br> Já estamos terminando... coloquem um nome de usuário. Inclusive, prazer, somos Barbarailum, gustavercosa, VictorPuntelRui e viyuetuki.
<br> Por fim, aprovem a inscrição! Teclem "y" e enviem.
<br>
<br> Iniciando as criações... 📎
<br> Primeiro, alguns apetrechos: o `GitHub` usa distintas ferramentas e vamos explicá-las sucintamente para vocês. 
<br> O `.gitignore` realiza a seleção de arquivos e/ou pastas que serão ignorados na criação de um novo repertório. Saiba mais em: https://docs.github.com/pt/get-started/getting-started-with-git/ignoring-files.
<br> Vamos gerar um repositório! Ao clicarem no seu respectivo ícone, selecionem a opção "Your profile", vocês serão direcionados para a página de usuário. Lá, acessem os repositórios em "Repositories".
<br> Para criar é simples. Cliquem em "New", no canto superior direito e o personalize: coloquem qualquer nome no espaço destinado, o "Repository name". Se quiserem, também podem especificá-lo adicionando um comentário em "Description".
<br> Em seguida, selecionem o tipo: público ou privado. Para fins acadêmicos, é recomendado usar o estilo "Public", pois vocês compartilharão informações entre si.
<br> Por fim, "enfeite" seu repertório: vocês querem um arquivo `README`? Quais arquivos vocês querem ignorar com o `.gitignore`? Qual licença vocês usarão? Essa última seleção é delicada! A licença é o que determina como e se ocorrerá o compartilhamento legal de informações contidas no `GitHub`. Cada uma atua de uma forma diferente, então, estude-as! Saiba mais em: https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository.
<br> Pronto, vocês pode terminar de estruturar seu repertório clicando em "Create repository".

Na interface do terminal, podemos ultilizar os seguintes comandos para gerenciar as pastas e edita-las:

git status - Mostra o branche em que se esta atualmente. Branche é uma maneira de editar os arquivos sem alterar os originais, então basicamente é criada uma cópia deles, um "universo paralelo" em que voce realiza as alterações que quiser e após isso pode fundi-lo com o arquivo original, sem risco de estragar algo que havia feito anteriormente.

git clone (link) - Este comando copia os arquivos do Git Hub para uma pasta em seu computador. Para ultiliza-lo basta apenas digitar "git clone" e ao lado colocar o link do seu projeto. Esse link vai estar disponivel no canto superior direito de seu commit, em verde.
Exemplo : git clone https://github.com/VictorPuntelRui/PCD.git

git checkout (branche) - entrar em um branche específico. 
Para trocar de "universo paralelo" e transitar entre eles, ultilizamos esse comando. Ao escrever "git chechout" e ao lado indicar para qual branche voce quer ir, ele irá te direcionar para tal.
Exemplo : git checkout universo2
universo2 nesse caso é um branche criado.

git cd (arquivo) - Esse código ultilizamos para entrar em uma pasta específica. Funciona de maneira similar aos anteriores, digite "git cd" e ao lado escreva  a pasta que quer acessar.
Exemplo: git cd tutorial_GitHub.
