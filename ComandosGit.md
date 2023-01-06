<h1>Comandos GIT</h1> 

git add .                 = Adiciona todas modificações.

git commit  -am "add api" = Adiciona nome para commit que será realizado.

git pull                  = Verifica e baixa atualizações feitas no  repositorio.

git push                  = Envia as modificações efetuadas pra o repositorio.

git checkout -b dev       = Cria nova branch com nome DEV.

git switch main           = Troca para branch MAIN ou DEV.

git push origin dev       = envia as modificações para a branch DEV.

git branch                = Mostra a branch que esta trabalhando.

git merge dev             = Pega as modificações que foram feitas na branch DEV e envia para branch que você estiver (usar antes o git switch main pra ir pra branch main e pegar as modificações necessárias, e usa o git push origin main para enviar as alterações para o respositorio GIT).

git restore --source c78b605 (nome do commit que quer restaurar), depois usa o git commit -am "..." e manda o git push.
