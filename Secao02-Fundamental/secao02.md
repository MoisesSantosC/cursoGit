# Sobre esta seção

- O que é um reposiório.
- Criando um repositório.
- O que é GitHub.
- Enviando repositório para o GitHub.
- Verificando as mudanças do projeto.
- Adicionando arquivos ao projeto.

---

## O que é um repositório

- É onde o código será **armazenado**.
- Na maioria das vezes cada projeto tem **um repositório**.
- Quando criamos um repositório estamos iniciando um projeto.
- O repositório pode ir para servidores que são especializados em gerenciar repositórios, como: **GitHub** e **Bitbucket**.
- Cada um dos desenvolvedores do time pode baixar o repositório e **criar versões diferentes** em sua máquina.

---

## Criando um repositório

- Para criar um repositório utilizamos o comando: `git init`
- Desta maneira o git vai criar os arquivos necessários para inicializá-lo.
- Que estão na pasta oculta **.git**.
- Após este comando o diretório atual **será reconhecido pelo git como um projeto** e responderá aos seus demais comandos.

---

## O que é GitHub

- É um **serviço para gerenciar repositórios**, gratuito e amplamente utilizado.
- Podemos **enviar nossos projetos** para o GitHub e disponibilizá-lo para outros devs.
- O GitHub é gratuito tanto para projetos públicos como **privados**.

---

## Enviando repositório para o GitHub

- Podemos facilmente **enviar nossos repositórios** para o GitHub.
- Precisamos criar o projeto no GitHub, inicializar o mesmo no git em nossa máquina, sincronizar e enviar.
- Esta sequência é facilmente executada **por poucos comandos**.
- Vale lembrar que só fazemos **uma vez por projeto** este fluxo.

---

## Verificando as mudanças do projeto

- As mudanças do projeto podem ser verificadas por: `git status`
- Este comando é utilizado **muito frequentemente**
- Aqui serão mapeados todas as alterações do projeto.
- Como: **arquivos não monitorados** e **arquivos modificados**.
- Podemos também dizer que é a **diferença** do que já está enviado ao servidor ou salvo no projeto.

---

## Adicionando arquivos ao projeto

- Para adicionar arquivos novos a um projeto utilizamos: `git add nomeDoArquivo`
- Podemos adicionar **um arquivo** específico.
- Também  podemos adicionar **diversos de uma vez só**: `git add .`
- Somente adicionando arquivos eles serão monitorados pelo git.
- Ou seja, **se não adicionar ele não estará** no controle de versão.
- É interessante utilizar este comando de tempos em tempos para não perder algo por descuido.

---
