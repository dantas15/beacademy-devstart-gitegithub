
# beacademy-devstart-gitegithub

![Screenshot readme.so](https://i.imgur.com/LJyvOfD.png)
*Screenshot do site utilizado para escrever este README*
<p align="center">
  <a href="#comandos">Comandos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instrutores">Instrutores</a>
</p>

Repositório das aulas sobre Git e Github do programa Devstart [Paylivre](https://www.paylivre.com/), da [BeAcademy](https://www.beacademy.com.br/).
Aqui temos os principais comandos utilizados no Git.

## Comandos

### Configuração

- [Adicionando uma chave SSH](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

- Configurar `user.name`

  ```bash
  # Configurando o nome global
    git config --global user.name "Seu Nome"
  ```

- Configurar `user.email`

  ```bash
  # Configurando o email global
    git config --global user.name "seuEmail@teste.com"
  ```

## Git flow

- Mostra o estado do projeto atual

  ```bash
  git status
  ```

- Mostra o log completo

  ```bash
  git log
  ```

- Inicializa o `git` no diretório atual

  ```bash
  git init
  ```

- Prepara os arquivos para `commit`

  ```bash
    git add # caminho para o arquivo
  ```

  *Pode-se usar o caractere . (ponto) para adicionar todas as alterações e modificações*

- Remove os arquivos rastreados pelo `git`

  ```bash
  git rm #arquivo
  ```

  - [Informações adicinais do git rm](https://www.atlassian.com/br/git/tutorials/undoing-changes/git-rm)

- Mostra todas as branches disponíveis

  ```bash
  git branchg
  ```

- Cria uma branch (2 formas)
  - `branch`

    ```bash
    git branch #nome-da-branch
    ```

  - `checkout` - Muda para a branch recém-criada

    ```bash
    git checkout -b #nome-da-branch
    ```

- Mudar para outra branch
  - `switch`

    ```bash
    git switch #nome-da-branch
    ```

  - `checkout`

    ```bash
    git checkout #nome-da-branch
    ```

- Remover branch localmente

  ```bash
  git branch -d #nome-da-branch
  ```

- Mesclar branch específicada na branch atual

  ```bash
  git merge #nome-da-branch que será mesclada na atual
  ```

- Adicionar um repositório remoto

  ```bash
  git remote add origin #link do repo remoto
  ```

- Enviar mudanças locais para o repositório remoto

  ```bash
  git push
  ```

- Arquiva mudanças (de um commit) em uma lista de `stash`

  ```bash
  git stash
  ```

- Mostra os stashes

  ```bash
  git stash list
  ```

- Seleciona um stash

  ```bash
  git stash apply@{indice}
  ```

- Volta no stash mais recente

  ```bash
  git stash pop
  ```

  - Volta à partir do índice

    ```bash
    git stash pop stash@{indice}
    ```

## Ferramentas

- [Readme.so](https://readme.so/)

## Instrutores

- [@rejota23](https://github.com/rejota23)
- [@lnmont](https://www.github.com/lnmont)
