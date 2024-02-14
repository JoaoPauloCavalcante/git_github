Olá, esse projeto ensina você a usar o Git.

*** PRINCIPAIS COMANDOS GIT ***

git --version (consultar a versão)
git init (inicializar um repositório git vazio, na branch master)
git add (manda os arquivos para a área de staging. basicamente, prepara os arquivos para serem enviados para a cloud)
git status (verifica o status dos arquivos no repositório)
git commit -m "mensagem" (usado para efetuar a atualização no arquivo LOCALMENTE. A mensagem serve para descrever o que aquela mudança representa)
git branch -M "main" (uma maneira de renomear a branch que eu estou)
git remote add origin "url" (criar a conexão do repositório do github com o repositório local)
git push -u origin "branchname" (enviar as mudanças para o github)

Testando uma nova linha

git reflog (comando que mostra o histórico de versões)
git reset -- hard (id_da_versao) (para voltar à uma versão específica. Deve-se usar o ID da versão)

git branch (listar as branches disponíveis)
git branch "nome_nova_branch" (criar uma nova branch)
A branch atual ficará marcada em verde e com um asterisco
git checkou "nome_branch" (utilizado para trocar de branch)