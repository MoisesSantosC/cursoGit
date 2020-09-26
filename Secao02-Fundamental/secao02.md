# Sobre esta seção

- O que é um reposiório.
- Criando um repositório.
- O que é GitHub.
- Enviando repositório para o GitHub.
- Verificando as mudanças do projeto.
- Adicionando arquivos ao projeto.
- Salvando alterações do projeto.
- Enviando código ao repositório remoto.
- Recebendo as mudanças.

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

## Salvando alterações do projeto

- As alterações salvas do projeto são realizadas por: `git commit`
- Podemos fazer commits de **arquivos específicos** ou vários de uma vez com a flag `-a`
- É uma boa prática enviar **uma mensagem a cada commit**, com as alterações que foram feitas.
- A mensagem pode ser adicionada com a flag `-m`
- Exemplo de somente um arquivo: `git commit nomeDoArquivo -m "Aqui vai a mensagem do seu commit"`
- Exemplo de vários arquivos: `git commit -a -m "Aqui vai a mensagem do seu commit"`

---

## Enviando código ao repositório remoto

- Quando finalizamos uma funcionalidade nova, **enviamos o código ao repositório remoto**, que é o código fonte.
- Esta ação é feita pelo `git push`
- Após esta ação **o código do servidor será atualizado baseando-se no código local** enviado.

---

## Recebendo as mudanças

- É comum também ter que **sincronizar o local** com as mudanças do remoto.
- Esta ação é feita pelo `git pull`
- Após o comando serão **buscadas atualizações**, se encontradas elas **serão unidas ao código atual** existente na nossa máquina.

---
