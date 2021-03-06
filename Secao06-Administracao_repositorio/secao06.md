# Tópicos desta seção

- Limpando arquivos untracked
- Otimizando o repositório
- Checando a integridade de arquivos

---

## Limpando arquivos untracked

- O comando `git clean -f` vai verificar e limpar arquivos que não estão sendo trackeados.
- Ou seja, todos os arquivos que **não utilizamos o** `git add`.
- Utilizado para arquivos que são **gerados automaticamente**, onde atrapalham a visualização do que é realmente importante.

---

## Otimizando o repositório

- O comando `git gc` é uma abreviação para **garbage collector**.
- Ele identifica arquivos que **não são mais necessários** e os exclui.
- Isso fará com que o repositório seja otimizado em questões de performance.

---

## Checando a integridade de arquivos

- O comando `git fsck` é uma abreviação de File System Check.
- Esta instrução verifica a integridade de arquivos e sua conectividade.
- Verificando assim possíveis **corrupções em arquivos**.
- **Comando de rotina**, utilizado para ver se está tudo certo com nossos arquivos.

---
