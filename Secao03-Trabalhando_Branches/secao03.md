# Sobre esta seção

- O que é um branch
- Criando e visualizando o brach
- Deletando branches

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
