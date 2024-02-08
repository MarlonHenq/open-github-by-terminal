# open-github-by-terminal

Esté código é um scrip para poder chamar o GitHub via terminal.

# Instalação

Copie o arquivo `github` para a pasta `/usr/local/bin/` e dê permissão de execução.

```bash
sudo cp github /usr/local/bin/
sudo chmod +x /usr/local/bin/github
```

Faça o seu bash atualizar os comandos.

```bash
source ~/.bashrc
```

# Utilização

## Abrir Github
Para abrir o GitHub no seu navegador, basta digitar `github` no terminal.

```bash
github
```

## Abrir um repositório

Para abrir um repositório, basta digitar `github -r` seguido do nome do repositório.

```bash
github -r nome-do-repositorio
```

## Abrir uma organização

Para abrir uma organização, basta digitar `github -o` seguido do nome da organização.

```bash
github -o nome-da-organizacao
```

## Abrir um repositório em uma organização

Para abrir um repositório em uma organização, basta digitar `github -or` seguido do nome da organização e seguido do nome do repositório.

```bash
github -or nome-da-organizacao nome-do-repositorio
```

## Abrir um projeto em uma organização

Para abrir um projeto em uma organização, basta digitar `github -op` seguido do nome da organização e seguido do nome do projeto.

```bash
github -op nome-da-organizacao nome-do-projeto
```

## Adicionar um shortcut

Para adicionar um shortcut basta digitar `github -s` e em seguida o nome do shortcut, o um link para um repositório ou organização...

```bash
github -s nome-do-shortcut link
```

## Para chamar um shortcut

Para chamar um shortcut basta digitar `github -a` e em seguida o nome do shortcut.

```bash
github -a nome-do-shortcut
```

# Contribuição

Para contribuir com o projeto, basta fazer um fork e enviar um pull request.
