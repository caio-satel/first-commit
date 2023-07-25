# Aprendendo Git e GitHub

<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>

# Indice

* [Titulo do Projeto](#aprendendo-git-e-github)
* [Indice](#indice)
* [Descrição do Projeto](#descrição-do-projeto)
* [O que fazer? Como fazer?](#o-que-fazer-como-fazer)


# Descrição do Projeto

Projeto de aprendizado em Git e GitHub, trabalhando localmente, commits, git.dev, trabalho em equipe e adicionando arquivos. Essas são algumas funcionalidades importantes para você ter controle total do seu projeto e poder compartilhar com outros colaboradores.

Esse conteúdo é importantissímo para quem está iniciando na programação e ira facilitar sua vida com o versionamento de código e trabalho em equipe. Bom para se familiarizar com esse método que a maioria das empresas utilizam.

# O que fazer? Como fazer?

- `Passo 1:` Vamos clonar o projeto do GitHub para sua máquina, abra o CMD, escolha o diretório que deseja clonar esse projeto e utilize esse código para realizar esta ação:
```
git clone "https://github.com/user-name/nome-repositório.git"
``` 

Essa URL é possível encontrar no GitHub, na página do seu repositório, clicando no botão verde "<> Code".

- `Comandos importantes:` 

Depois de clonado para sua máquina, importante verificar o estado do projeto digitando no prompt de CMD, isso irá verificar se há alguma alteração no projeto:

```
git status
```

Importante também é verificar se não foi realizado algum commit no projeto por outro colaborador, pra isso realize esse comando: 

```
git pull
```

Para adicionar as mudanças ao repositório local, podemos usar:

```
git add .
```
Ele irá adicionar todas as mudanças de uma só vez. Caso queira adicionar um arquivo específico, use: 

```
git add nome-do-arquivo-alterado
```

Para salvar alterações utilize o comando: 

```
git commit <nome-arquivo-alterado> -m "descrição da alteração"
```

Para enviar as modificações do repositório local ao repositório remoto, utilize o comando: 
```
git push
```