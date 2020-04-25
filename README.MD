# Git estudos

## O que é?

## Como surgiu?

## Problemas que resolve?

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

### Criando branch

### Navegando entre branch

### Excluindo branch

### Mesclando branch

### Desfazendo mudanças

# Referências: 

[Roger Dudler](https://rogerdudler.github.io/git-guide/index.pt_BR.html)