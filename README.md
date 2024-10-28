# 📚 Aprendendo Git e GitHub

Bem-vindo ao repositório de aprendizado de Git e GitHub! Este guia foi criado para ajudar iniciantes a entenderem e dominarem as funcionalidades essenciais dessas ferramentas fundamentais para o desenvolvimento de software.

## 📋 Sumário

- [Introdução](#introdução)
- [Pré-requisitos](#pré-requisitos)
- [Conceitos Básicos](#conceitos-básicos)
- [Comandos Essenciais](#comandos-essenciais)
- [Fluxo de Trabalho](#fluxo-de-trabalho)
- [Boas Práticas](#boas-práticas)
- [Exercícios Práticos](#exercícios-práticos)
- [Recursos Adicionais](#recursos-adicionais)

## 🚀 Introdução

Git é um sistema de controle de versão distribuído que permite que você acompanhe mudanças no código-fonte durante o desenvolvimento de software. GitHub é uma plataforma baseada na web para hospedar e colaborar em repositórios Git.

## 💻 Pré-requisitos

- Instalar o Git em sua máquina
- Criar uma conta no GitHub
- Conhecimento básico de linha de comando
- Editor de texto ou IDE de sua preferência

## 🔑 Conceitos Básicos

### Repositório
Um repositório é onde seu projeto vive. Pode ser local (na sua máquina) ou remoto (como no GitHub).

### Branch
Uma ramificação do seu projeto que permite desenvolvimento paralelo sem afetar o código principal.

### Commit
Um snapshot das mudanças em seu código em um determinado momento.

## 📝 Comandos Essenciais

```bash
# Configuração inicial
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

# Iniciar um repositório
git init

# Clonar um repositório
git clone <url-do-repositório>

# Verificar status
git status

# Adicionar arquivos
git add <arquivo>
git add .  # adiciona todos os arquivos

# Fazer commit
git commit -m "mensagem do commit"

# Enviar alterações
git push origin main

# Atualizar repositório local
git pull origin main

# Criar branch
git branch <nome-da-branch>

# Mudar de branch
git checkout <nome-da-branch>
```

## 🔄 Fluxo de Trabalho

1. **Clone/Init**: Inicie ou clone um repositório
2. **Branch**: Crie uma branch para sua feature
3. **Alterações**: Faça suas modificações
4. **Stage**: Adicione as alterações (git add)
5. **Commit**: Faça commit das alterações
6. **Push**: Envie para o repositório remoto
7. **Pull Request**: Solicite a revisão do código
8. **Merge**: Após aprovação, mescle com a branch principal

## ✨ Boas Práticas

- Mantenha commits pequenos e focados
- Escreva mensagens de commit claras e descritivas
- Faça pull antes de push
- Nunca faça commit diretamente na main/master
- Mantenha seu repositório local atualizado
- Use .gitignore para arquivos que não devem ser versionados

## 🎯 Exercícios Práticos

1. **Exercício Básico**
   - Crie um repositório local
   - Adicione alguns arquivos
   - Faça commit e push para o GitHub

2. **Trabalho com Branches**
   - Crie uma nova branch
   - Faça algumas alterações
   - Merge com a branch principal

3. **Resolução de Conflitos**
   - Simule um conflito
   - Aprenda a resolver conflitos
   - Complete o merge

## 📚 Recursos Adicionais

- [Documentação oficial do Git](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [GitHub Learning Lab](https://lab.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## 🤝 Contribuindo

Sinta-se à vontade para contribuir com este repositório! Você pode:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abrir um Pull Request



---

⭐ Se este repositório te ajudou, não esqueça de deixar uma estrela!

📧 Dúvidas? Abra uma [issue](../../issues) ou entre em contato.
