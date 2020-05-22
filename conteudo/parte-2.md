[Parte anterior](/conteudo/parte-1.md) | [Próxima parte](/conteudo/parte-3.md)

---

# Comandos Git
Para começar a explorar os comandos básicos do Git, crie um diretório no seu computador `tutorial-git-github`. Vamos abrir essa pasta no terminal. Certifique-se 
de ter o Git instalado no seu computador.

**Windows:** abra a pasta no Explorador de Arquivos, e clique com o botão direito 
em uma parte vazia da pasta. Dentre as opções, clique em "Abrir Git Bash aqui". Você deve ver uma janela de terminal se abrir no diretório `tutorial-git-github`. Algo assim:

<img src="../.github/parte-2/git-bash.png" width="600">


## `git init`
Inicia um **repositório** Git e cria um diretório `.git` onde serão armazenadas as alteraçãoes que ocorrerem no arquivos que forem rastreados.

```sh
.../tutorial-git-github$  ls -a # mostre o que há nesse diretório, incluindo arquivos e pastas escondidas (-a)
.     # diretório atual
..    # diretório pai/diretório anterior
.git
```

Onde fica `.git` é conhecido como diretório raíz do repositório. É geralmente daqui que serão executados todos os comandos, a não ser que o contrário seja especificado.

## `git status`
Mostra quais arquivos estão no **stage**, 
quais estão **unstaged** (não estão no stage),
e quais estão **untracked** (não estão sendo rastreados).
_Stage_ ("palco") é uma área em que alterações nos arquivos estão prontas para serem "commitadas", ou entrarem para a história do repositório.


Se um arquivo não está sendo rastreado, as alterações que ele sofre _não_ entram para a história do repositório e para ele não há controle de versão. Regra geral: um arquivo será rastreado se ele passar pelo `git add` individualmente ou em grupo.

## `git add`
Adiciona arquivos e pastas no rastreio do Git.

`git add <nome-do-arquivo>` para adicionar as alterações no **staging area**.
    exemplo: `git add index.html`

Se você deseja adicionar todas as alterções no próximo commit:
`git add -A`

## `git commit -m`
- `git commit`
- `git commit -m`


## Ciclo de vida
<img src="../.github/parte-2/lifecycle.png" width="600">


## `git push`
- Explicar que `origin` é o nome de uma variável, um alias pra URL
- `git push origin master`
- `git push -u`

## `git pull`

## `git remote`
Comandos relacionados ao repositório remoto (pode ser no Github, Gitlab, Bitbucket etc)
- `git remote -v`
- `git remote add origin <url>`
- `git remote set-url origin <url>`

## `git log`
- `git log`
- `git log --oneline --graph`

## `git branch`
- `git branch <nome-da-branch>`
- `git branch -d <nome-da-branch>`

## `git checkout`
- `git checkout <nome-da-branch>`
- `git checkout -b <nome-da-branch>`


---
[Parte anterior](/conteudo/parte-1.md) | [Próxima parte](/conteudo/parte-3.md)