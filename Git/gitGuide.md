# Git Guide

Ferramenta de gerenciamento de código completa, permitindo controle de versões, assegurando rastreabilidade de mudanças, flexibilizando colaboração da equipe e, em parceria com serviços online, possibilitando o armazenamento e núvem.

> Alguns exemplos de serviços são:
> GitHub, GitLab, Bitbucket, Azure Repos, AWS CodeCommite e Google Cloud Source Repositories.

## Git

É a ferramenta principal para comunicação entre qualquer repositório. Para isso, a instalação local é necessária, mesmo que IDEs como VSCode e Cursor conheçam os comandos.

Para saber se a mesma já está instalada, execute o comando no terminal:
```sh
git --version
```

Caso não tenha instalado, acesse:
[Site para download]

Após instalação, o ideal é que se configure as informações que serão utilizadas de forma padrão, como o usuário e o e-mail:

Para conferir:

```sh
git config --global user.name
git config --global user.email
```

Para realizar a alteração de forma global:

```sh
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Tudo configurado, o início de um novo repositório é possível através do comando:

```sh
git init -y
```

Sempre que quiser saber o status do repositório:

```sh
git status
```

Para adição dos arquivos no repositório, incluindo todos os arquivos ou um específico:

```sh
git add .
git add "arquivo"
```

Complementando sempre com um comentário após cada mudança:

```sh
git commit -m "comentario"
```

Com isso, é possível adicionar um repositório remoto:

```sh
git remote add origin (link)
```

E para fazer o upload pela primeira vez, já deixando a branch estabelecida:

```sh
git push -u origin main
git push
```

E em caso de um upload específico para uma branch

```sh
git push origin main
```

Em um repositório já criado, pode-se conferir as informações de commit:

```sh
git config user.name
git config user.email
```

Já para modificar apenas no repositório 'atual':

```sh
git config user.name "Seu Nome"
git config user.email "seuemail@example.com"
```

Para conferir se o repositório remoto está correto e caso queira mudá-lo:

```sh
git remote -v
git remote set-url (link)
```
### Configurações gerais de branchs
git remote show origin

[//]: #
[Site para download]: <https://git-scm.com/>