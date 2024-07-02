# github_teoria

### Resumo

```
git init                                                             Inicializa um novo repositório
git add .                                                            Adiciona os arquivos atuais ao próximo commit
git status                                                           Verificar o status atual dos repositório git
git commit -m "mensagem do commit"                                   Cria um novo commit com uma mensagem
git push                                                             Envia as atualizações para a nuvem da branch atualmente ativa
git branch                                                           Permite listar e ver qual branch está ativa atualmente
git checkout nome-da-branch                                          Permite mudar para uma nova branch
git checkout -b "nome da branch de origem" "nome da nova branch"     Permite mudar e criar uma nova branch com base em outra
git merge "branch a receber merge"                                   Permite fazer o merge da branch ativa atualmente com outra branch
git pull                                                             atualiza a branch atualmente ativa
```
echo "# teste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://git...
git push -u origin main
```

### Corrigir uma mensagem de commit errada

```
git commit -m "mensagem que você quer recolocar" -amend
```

### Remover arquivo de stage (git add)

```
git reset HEAD -- path/to/file
```
Just like "git add", you can unstage files recur directory and so forth, so to unstage everthing run this from the root directory of your repository

```
git reset HEAD -- .
```

### Use aspas para nomes que são divididos por espaço

```
"c:\my file name" "d:\my new file name"
```
