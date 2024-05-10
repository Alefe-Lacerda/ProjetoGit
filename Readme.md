Olá! Esse projeto ensina a usar o git.

Iniciando o git:
1. Clique no botão direito do mouse na pasta, então escolha "Open git bash here"
2. Após isso, abrirá o git bash, vc então escreverá "git init"
3. Irá aperecer q foi inicializado um repositório vazio e depois um "(Master)" indicando q aquela é a Branch principal
4. Irá aparecer uma pasta ".git": Aqui acontece tudo do git, todas as coisas q ficam armazenadas, ficam armazenadas ali, então !!!NÃO APAGUE A PASTA .git!!!



Dando um Commit no git:
1. Commit são as versões do arquivo
2. "git add" é um tipo de "preparação para entrar no palco", é um último suspiro antes de entrar de fato no palco
3. Exemplo: "git add Readme.md" para dar um git add no arquivo Readme.md
4. Quando vc der um "git status" vc vai ver o status dele, está "on branch master" mas "no commits yet"
5. Finalmente, vc dá um "git commit -m "uma mensagem q vc quiser, ou um título""
6. (Talvez não seja necessário, talvez seja) mude para a branch Main, escrevendo "git branch -M "main""
    Ps: Perceba q o M é maiúsculo



Dando um push no github:
1. Abra o github e crie uma pasta lá para isso
2. Dê um "git remote add origin -m github.com/seu_user/pasta_do_github"
3. Dê um "git push -u origin main"


Alterando arquivos:
1. "git add ." para mandar os arquivos alterados pro standing
2. "git commit -m "uma mensagem"" para mandar a nova versão
3. "git push origin main" para "empurrar" para o github (ps: não precisa mais do "-u")


Criando uma branch:
1. No git bash, digite: git checkou -b "nomeDaNovaBranch"
2. Para mudar de branch, digite: git checkou "nomeDaBranch"
3. Para juntar as versões, digite: git merge "nomeDaBranch"