# PL04 - Git (sessao04)

Trabalho prático de Git/GitHub para a disciplina (FCUP).

## 1. Criar conta no GitHub

Cada elemento do grupo criou, individualmente, uma conta em https://github.com/.
A conta dá acesso ao alojamento de repositórios remotos, à colaboração em projetos
e à integração com ferramentas como o GitHub Desktop e o GitHub Classroom.

## 2. Instalar GitBash e GitHub Desktop

- **Git Bash** (parte do pacote *Git for Windows*): instalado a partir de
  https://git-scm.com/install/windows. Disponibiliza um terminal com os comandos
  `git`, permitindo trabalhar com o repositório através da linha de comandos.
- **GitHub Desktop**: instalado a partir de https://github.com/apps/desktop e
  associado à conta GitHub criada no ponto 1. Oferece uma interface gráfica
  para realizar `commit`, `branch`, `merge`, `push` e `pull` sem usar o terminal.

## 3. Criar projeto e adicionar repositório (sessao04) com o GitHub Desktop

No GitHub Desktop foi criado um novo projeto local correspondente a esta tarefa
(*File → New repository...*), com o nome **`sessao04`**, na pasta de trabalho do
utilizador. Em alternativa o repositório pode ser inicializado no terminal com
`git init -b main` e ligado ao remoto através de
`git remote add origin <URL>`.

## 4. Sincronizar o repositório local com o remoto

Após o primeiro `commit`, o repositório local foi sincronizado com o remoto
(`origin`) através de `git push -u origin main` (na primeira sincronização) e
posteriormente com `git push` / `git pull`. No GitHub Desktop a mesma operação
é feita pelo botão **"Push origin"** / **"Fetch origin"**.
