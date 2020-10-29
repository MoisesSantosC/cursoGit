# Tópicos desta seção

- Encontrando branches
- Recebendo alterações
- Enviando alterações
- Utilizando o remote
- Trabalhando com submódulos

---

## Encontrando branches

- Branches novos são criados a todo tempo e o **seu git pode não estar mapeando eles**.
- Com o comando `git fetch` você é atualizado de todos os branches e tags que ainda não estão reconhecidos por você.
- Este comando é útil para utilizar o branch de algum outro desenvolvedor do time, por exemplo.

---

## Recebendo alterações

- O comando `git pull` serve para recebermos atualizações do repositório remoto.
- Cada branch pode ser atualizado com o `git pull`
- Utilizamos para atualizar a master do repositório e também quando trabalharmos em conjunto e queremos receber as atualizações de um desenvolvedor.

---

## Enviando alterações

- O comando `git push` faz o inverso do pull, ele envia as alterações para o repositório remoto.
- Serve também para **enviar as atualizações de um branch específico** para um outro desenvolvedor.
- Ou quando terminamos uma tarefa e precisamos enviar ao repositório.

---

## Utilizando o remote

- Com o comando `git remote` podemos fazer algumas ações como: adicionar um repositório para trackear ou remover.
- Quando criamos um repositório remoto, adicionamos ele ao git com `git remote add origin linkDoRepositório`
- Com o `git remote -v` podemos verificar as origins para darmos o fetch ou o push.
- Para remover `git remote rm origin`

---

## Trabalhando com submódulos

- Submódulos é a maneira que temos de possuir **dois ou mais projetos em um só repositório**
- Podemos adicionar uma dependência ao nosso projeto atual, porém mantendo suas estruturas separadas.
- Para adicionar o submódulo utilizamos o comando `git submodule add nomeDoRepositório`
- Para verificar os submódulos o comando é `git submodule`

---
