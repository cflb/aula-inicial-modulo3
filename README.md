# Criar um repositório GIT no GITHub

## Primeiro Passo 
> Instalar o Git

## Segundo Passo
1. Crie uma pasta para abrigar os arquivos do seu projeto

> mkdir nome-da-pasta

2. Entre na pasta que você criou

> cd nome-da-pasta

3. Inicializar o seu repositorio Git

> git init

## Terceiro Passo

### Monitorando repositório GIT

> git status

### Conectar o Repostório Local com o Repositório Remoto no GitHub

```
É necessário adicionar ao git o repositório remoto do github,
para isso execute o segunte comando:
```

> git remote add origin https://github.com/seu_suaurio/nome_do_repositiro.git


```
Enviando os dados do repositório local para o repositório no github
```

> git push origin main 

### Modificando a bransh atual

```
Para criar uma nova bransh use o seguinte comando:
```

> git checkout -b explicado-como-adiciona-novas-bransh


```
Ao finalizar o fluxo de trabalho, vou adicionar e commitar meus arquivos, e 
enviar para a nova origin, com o comando a baixo:
```

> git push origin explicado-como-adiciona-novas-bransh

### Como Clonar um Repositório Git no Github

```
Para clonar um repositório remoto no github, primeiro, copie o endereço preferencialmente
o HTTPS do seu repositório. Depois digite o seguinte comando:
```

> git clone a_URL_do_seu_repositorio

Ex.:

> git clone https://github.com/cflb/aula-inicial-modulo3.git

```
Após a clonagem do repositório entre nele e faça as modificações necessárias
```

> cd aula-inicial-modulo3

```
Uma vez que modificações foram feitas, execute o fluxo git para monitorar, comitar e enviar
os arquivos para o repositório Remot.
```

> git push origin nome-da-branch

Ex.:

> git push origin main
