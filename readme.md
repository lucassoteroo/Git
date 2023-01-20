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