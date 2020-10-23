# Sobre esta seção

- O que é um branch
- Criando e visualizando o brach
- Deletando branches
- Mudando de branch
- Unindo Branches

---

## O que é um branch

- Branch é uma forma que o git **separa as versões dos projetos**.
- Quando um projeto é criado ele inicia na branch **master**.
- Geralmente cada nova feature de um projeto **fica em uma branch separado**
- Após a finalização das alterações os **branches são unidos** para ter o código-fonte final.

---

## Criando e visualizando o brach

- Para visualizar os branches disponíveis basta digitar `git branch`
- Para criar um branch você pode utilizar o comando `git branch nomeDaBranch`

---

## Deletando branches

- Podemos deletar um branch com a flag `-d` ou `--delete`
- **Não é comum deletar um branch**, normalmente é guardado o histórico do trabalho.
- Geralmente se usa o **delete** quando o branch foi criado errado.
- Exemplo: `git branch --delete nomeDaBranch`

---

## Mudando de branch

- Podemos mudar para outro branch utilizando o comando `git checkout nomeDaBranch`
- Podemos mudar para outro branch e criar esse branch ao mesmo tempo: `git branch -b nomeDaBranch`
- Este comando também é utilizado para dispensar mudanças de um arquivo.
- Alterando o branch podemos levar alterações que não foram commitadas junto, **tome cuidado**.

---

## Unindo Branches

- O código de dois branches distintos pode ser unido pelo comando `git merge nomeDaBranch`
- Normalmente é por meio dele que recebemos as atualizações de outros desenvolvedores.

---

## Stash

- Podemos salvas as modificações atuais **para prosseguir com uma outra abordagem de solução** e não perder o código.
- O comando para esta ação é o `git stash`
- Após o comando, o branch será resetado para a sua versõ de acordo com o repositório.
- Podemos verificar as stashes criadas pelo comando: `git stash list`

---

## Recuperando stash

- Podemos recuperar o stash com o comando: `git stash apply aquiVaiONumeroDaStash`
- Desta maneira podemos continuar de onde paramos com os arquivos adicionados a stash.
- Para ver a diferença dos stashes basta usar o comando: `git stash show -p aquiVaiONumeroDaStash`

---

## Removendo a stash

- Para limpar totalmente as stashes de um branch podemos utilizar o comando `git stash clear`
- Caso seja necessário deletar uma stash específica podemos utilizar `git stash drop aquiVaiONumeroDaStash`

---
