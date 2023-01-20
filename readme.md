- Alterar nome do usuário:

```sh
git config --global user.name "Seu Nome"
```

- Alterar email do usuário:

```sh
git config --global user.email "seuemail@gmail.com"
```

- Criar novo repositório git:

```sh
git init
```

- Verifica estados das alterações:

```sh
git status
```

- Adiciona alterações para staged area:

```sh
git add <arquivo/pasta>
```

- Adiciona todas as alterações para staged area:

```sh
git add .
```

- Commita alterações:

```sh
git commit <arquivo>
```

- Commita alterações com uma mensagen:

```sh
git commit <arquivo> -m "mensagem do commit"
```

- Commita alterações que já estejam em staged area:

```sh
git commit
```

- Commita alterações, com uma mensagem, que já estejam em staged area:

```sh
git commit -m "mensagem do commit"
```

- Remove arquivo: 

```sh
git rm <arquivo>
```

- Remove pasta/diretório:

```sh
git rm -r <pasta/diretório>
```

- Exibe histórico de commits:

```sh
git log
```

- Exibe histórico de commits em uma linha:

```sh
git log --oneline
```

- Exibe repositórios remotos:

```sh
git remote
```

- Vincula repositório local com remoto:

```sh
git remote add origin <url do projeto>
```

- Envia alterações para o repositório remoto:

```sh
git push
```

- Atualiza repositório local de acordo com o repositório remoto:

```sh
git pull
```

- Clona o repositório remoto já existente:

```sh
git clone <url do projeto>
```

- Cria uma tag:

```sh
git tag <nome da tag>
```

- Cria tag com anotação:

```sh
git tag -a <nome da tag> -m "Versão 1.0"
```

- Cria tag a partir de um commit:

```sh
git tag -a <nome da tag> <commit>
```

- Envia tag para repositório remoto:

```sh
git push <nome da tag>
```

- Cria todas as tags para o repositório remoto:

```sh
git push --tags
```

- Cria uma branch:

```sh
git branch <nome da branch>
```

- Troca para uma branch já existente:

```sh
git checkout <nome da branch>
```

- Cria e troca automaticamente para a nova branch:

```sh
git checkout -b <nome da branch>
```

- Mergea a branch selecionada na branch atual:

```sh
git merge <nome da branch>
```

- Lista as branchs existentes:

```sh
git branch
```

- Lista as branchs já mergeadas:

```sh
git branch --merged
```

- Lista as branchs não mergeadas:

```sh
git branch --no-merged
```

- Cria um stash:

```sh
git stash
```

- Lista o stashs existentes:

```sh
git stash list
```

- Aplica o último stash:

```sh
git stash apply
```

- Aplica um stash específico:

```sh
git stash apply stash@{0}
```

- Apagar um stash:

```sh
git stash drop stash@{0}
```

- Altera mensagem de um commit já existente no repostório remoto:

```sh
git commit --amend -m "Nova mensagem"
```

- Exibe alterações dentro da linha da código:

```sh
git diff
```

- Exibe alterações dentro da linha da código de um commit específico:

```sh
git diff <commit>
```

- Revert o commit:

```sh
git commit <HEAD/commit>
```

> Apenas local 

- Desfaz o último commit:

```sh
git reset --hard HEAD
```

- Desfaz quantos commits for indicado pelo número:

```sh
git reset --hard HEAD~1
```

- O commit é desfeito, porém as alterações não são perdidas, faltando adicionar e commitar:

```sh
git reset --mixed <commit/HEAD>
```

- o commit é desfeito, porém as alterações não são perdidas, faltando apenas commitar:

```sh
git reset --soft  <commit/HEAD>
```
