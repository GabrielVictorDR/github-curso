# Github

Este é um repoistorio para aprender como o Git funciona!

Esta linha serve como exemplo para modificações no arquivo a ser add.

Hello World... Again!

## Decorando comandos

### Iniciais

git init (inicia um repoisitório dentro de um determinado diretorio do PC - cria a .git).

git status (mostra o status atual do diretorio, ou seja, arquivos modificados, adicionados, etc).

git add (prepara os arquivos para serem commitados).

git commit -m "Texto informativo sobre o Commit".

git push -u origin master (envia o repositorio para a nuvem).

git log / shortlog (mostra todos os commits).

### Desfazendo coisas

git diff (mostra a diferença entre o arquivo antigo e o editado)

git checkout "Nome do arquivo" (retorna para antes da edição)

git reset --soft (volta para o commit anterior) --mixed --hard (remove completamente o commit) "codigo hash do commit anterior".

### Branchs

git branch (mostra todas as branchs no repositorio.)

git checkout -b "Nome da Branch" (cria uma nova brach).

git branch -D "Nome da Branch" (deleta).

git checkout "Nome da Branch" (navega para outra brunch).

git merge (une todos os commits anteriores em um novo, sem alterar a linha cronologica)

git Rebase (une todos os commits em uma unica linha cronologica).

### Apagando tags e Branchs do Repositorio remoto

git push origin :"nome da branch/tag"

