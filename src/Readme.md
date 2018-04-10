# Git Course Testing
# Comentario para teste com o .gitignore
# Teste do git stash
# Teste de Tag

[Youtube](http://youtube.com)

Link com alias para git : https://jonsuh.com/blog/git-command-line-shortcuts/

-mkdir : Cria uma nova pasta no diretório atual
-cd caminho : Muda o diretório para o diretório passado no caminho
-git init : Inicializa um repositorio na pasta atual
-git status : Mostra o status atual do repositório com todos os arquivos e seus status
-git add nome_do_arquivo : Muda o status do arquivo de 'untracked' para 'unmodified'
-git commit : Muda o status dos arquivos 'unmodified' para 'staged', prontos para serem enviados. (-m "Mensagem do commit", -am "Mensagem do commit")
-git log --graph : Mostra os commits atuais com informações.
    graph : Mostra uma representação gráfica dos branchs e commits.
-git shortlog : Mostra um log resumido
-git reset --soft --mixed --hard hash_do_commit : Reseta um trabalho feito em um commit. 
    soft = Altera o status de todos os arquivos do commit para 'staged', prontos para serem comitados.
    mixed = Altera o status de todos os arquivos do commit para 'unmodified', prontos para serem editados.
    hard = Remove todos os commits a partir do reset
-git checkout : 
-git branch : Mostra os branchs
-git stash : Separa um trabalho em andamento (Work In Progress) em um arquivo específico para poder ser isolado e recuperado depois no mesmo branch ou em outro.
Modificação
