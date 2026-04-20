# Git Bash

## O que é

O **Git Bash** é um terminal de linha de comandos para Windows, distribuído com
o pacote *Git for Windows* (https://git-scm.com/). Emula um ambiente Unix
(`bash`) por cima do Windows, permitindo executar tanto comandos `git` como
utilitários típicos de Unix (`ls`, `grep`, `ssh`, `curl`, ...).

## Para que serve

Permite controlar versões de ficheiros através do Git, comunicando com
repositórios locais e remotos (por exemplo no GitHub) sem necessidade de
interface gráfica.

## Comandos mais usados

| Comando | Descrição |
|---------|-----------|
| `git init` | Inicializa um repositório Git numa pasta |
| `git clone <url>` | Cria uma cópia local de um repositório remoto |
| `git status` | Mostra o estado dos ficheiros (staged, modified, untracked) |
| `git add <ficheiro>` | Adiciona alterações à *staging area* |
| `git commit -m "msg"` | Regista as alterações no histórico local |
| `git push` | Envia commits para o repositório remoto |
| `git pull` | Obtém alterações do remoto e funde-as com o local |
| `git branch` | Lista / cria branches |
| `git checkout <branch>` | Muda para outra branch |
| `git merge <branch>` | Funde a branch indicada na branch atual |
| `git log --graph --oneline --all` | Mostra o grafo do histórico |

## Vantagens

- Acesso a *todos* os comandos do Git (a interface gráfica expõe apenas um
  subconjunto).
- Útil para automatizar tarefas em scripts.
- Funciona da mesma forma em Windows, macOS e Linux.
