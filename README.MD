# Git estudos

## O que é?

Git é um sistema de controle de versões (VCS).

## Como surgiu?

Desenvolvido em 2005 por Linus Torvalds para o desenvolvimento do Kernel Linux.

## Problemas que resolve?

Através dele é possível desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

# Comandos mais utilizados:

### Iniciando repositório

Inicializa um novo repositório
```
git init
```

### Clonando repositório

Clona um novo repositório informando a origem, tambem podendo alterar seu nome.
```
git clone <url do repositório>

git clone git@github.com:Havyner/git-estudos.git

git clone <url do repositório> <novo nome do repositório>

git clone git@github.com:Havyner/git-estudos.git meu-novo-repositorio
```

### Adicionando arquivos ao stage

Adiciona as mudanças para a etapa de **stage**.

Adiciona todos os arquivos ao stage.
```
git add .
```

Adiciona os arquivos conforme o nome informado.
```
git add <nome do arquivo>
```

Adiciona todos arquivos que terminam com a extenção informada.
```
git add *.extencao
```

### Registrando alterações

Registra as alterações na etapa final.
```
git commit -m "mensagem"
```

Registra alterações na etapa final e tambem adiciona os arquivos ao stage.
```
git commit -am "mensagem"
```

### Visualizando status

Exibe todos os arquivos que estão no stage e no workdir.
```
git status
```

### Enviando alterações

Envia as mudanças para o repositório remoto.
```
git push origin master
```

### Atualizando repositório local

```
git pull origin master
```

### Visualizando mudanças

Visualizar o histórico de mudanças gravadas no repositório.

```
git log
```

Visualizando apenas os 2 últimos commits.
```
git log -n 2
```

Visualizando resumo de commits.
```
git log --oneline
```

Visualizando arquivos alterados
```
git log --stat
```

Visualizando mudanças ainda não rastreadas
```
git diff
```

### Criando branch


Criando uma nova branch a partir do último commit da master.
```
git branch NomeDaBranch
```

Criando uma nova branch e selecionando ela.
```
git checkout -b NomeDaBranch
```

### Navegando entre branch



### Excluindo branch

```
git branch -d NomeDaBranch
```

### Mesclando branch

```
git merge NomeDaBranch
```

### Desfazendo mudanças

Mudanças sem salva-lás:
```
git clean -fd
```

Desfazendo git add .
```
git reset
```

Desfazer todas as alterações de arquivos locais
```
git reset --hard
```

# Referências: 

[GIT Oficial](https://git-scm.com/)
<br/>
[Roger Dudler](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
<br/>
[Daniel Schmitz](https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)
<br/>
[Diego Fernandes](https://blog.rocketseat.com.br/iniciando-com-git-github/)
<br/>
[Tacio S. S.](https://medium.com/taciossbr/uma-introducao-ao-git-o-que-e-e-como-usar-1dd721a1e6b0)
<br/>
[Debora Priscila](https://www.oficinadanet.com.br/post/16111-o-que-e-e-como-funciona-o-git-e-github)
<br/>
[Evelyn Schmitz](https://blog.taller.net.br/git-parte-1-como-durgiu-a-ferramenta-de-controle-de-versao/)
<br/>
[Bruna Escudelario](https://imasters.com.br/desenvolvimento/os-4-comandos-git-que-todo-desenvolvedor-deveria-conhecer)