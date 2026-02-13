# Aprendendo-git-github
# Git e GitHub: Conceitos e Fluxo de Trabalho Básico

## 1. Introdução

Git é um sistema de controle de versão distribuído criado por Linus Torvalds.
Ele permite rastrear alterações em arquivos e coordenar trabalho entre múltiplos desenvolvedores.

GitHub é uma plataforma de hospedagem de código baseada em Git que facilita colaboração e versionamento remoto.

---

## 2. Conceitos Fundamentais do Git

### Repositório
É o local onde o histórico do projeto é armazenado.

### Commit
Registro de uma alteração no projeto.
Cada commit possui um identificador único (hash).

### Branch
Ramificação do projeto que permite desenvolver funcionalidades isoladamente.

### Merge
Processo de integrar alterações de uma branch em outra.

---

## 3. Estrutura do Git (Como ele funciona internamente)

O Git trabalha com três áreas principais:

1. Working Directory (Diretório de Trabalho)
2. Staging Area (Área de Preparação)
3. Repository (Repositório)

Fluxo básico:

Working Directory → git add → Staging Area → git commit → Repository

---

## 4. Fluxo de Trabalho Básico

### Inicializando um repositório

git init

### Adicionando arquivos

git add .

### Criando um commit

git commit -m "mensagem do commit"

### Conectando ao repositório remoto

git remote add origin URL_DO_REPOSITORIO

### Enviando para o GitHub

git push -u origin main

---

## 5. Trabalhando com Branches

Criando uma nova branch:

git checkout -b nova-feature

Listando branches:

git branch

Voltando para main:

git checkout main

Fazendo merge:

git merge nova-feature

---

## 6. Conclusão

O Git é uma ferramenta essencial para versionamento e colaboração.
Compreender seu fluxo interno é fundamental para evitar conflitos e manter organização no desenvolvimento.
Postei  com o obejetivo de compartilhar o meu conhecimento e começcar a minha trilha de projetos e anexar ideias, aberto a sugestões e dicas 

Aprender Git é essencial para qualquer desenvolvedor.
Ainda estou no começo, mas já consigo ver como essa ferramenta é poderosa.
