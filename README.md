# 🚀 Portfólio da Turma - Git & GitHub

Bem-vindo(a) ao projeto colaborativo da nossa turma! Este é um portfólio web onde cada aluno terá seu próprio card de apresentação. Através desta atividade, você irá praticar:

- ✅ Fork de repositórios
- ✅ Criação de branches
- ✅ Commits e push
- ✅ Pull Requests
- ✅ Resolução de conflitos
- ✅ Revisão de código

---

## 🎯 Objetivo

Criar colaborativamente uma página web com cards de apresentação de todos os alunos da turma. Cada aluno será responsável por adicionar seu próprio card ao projeto!

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de que você tem:

- Git instalado no seu computador
- Uma conta no GitHub
- Um editor de código (VS Code, Sublime, etc.)

---

## 🚀 Como Participar

### **Passo 1: Fork do Repositório**

1. Clique no botão **"Fork"** no canto superior direito desta página
2. Isso criará uma cópia do repositório na sua conta do GitHub

### **Passo 2: Clone o Repositório**

Abra seu terminal e execute:

```bash
git clone https://github.com/SEU-USUARIO/portfolio-turma-git.git
cd portfolio-turma-git
```

> 💡 **Dica:** Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub!

### **Passo 3: Crie uma Branch**

Antes de fazer qualquer alteração, crie sua própria branch:

```bash
git checkout -b card-seunome
```

Exemplo:
```bash
git checkout -b card-joao
```

### **Passo 4: Adicione Seu Card**

1. Abra o arquivo `index.html` no seu editor de código
2. Localize o comentário que diz `<!-- AQUI VOCÊS VÃO ADICIONAR SEUS CARDS -->`
3. Logo abaixo, adicione seu card seguindo este modelo:

```html
<div class="card">
    <div class="card-header">
        <div class="avatar">😎</div>
        <div class="card-info">
            <h2>Seu Nome Aqui</h2>
            <div class="role">Estudante de Programação</div>
        </div>
    </div>
    <div class="card-body">
        Escreva uma breve descrição sobre você! Conte um pouco 
        sobre seus interesses em programação ou o que você quer aprender.
    </div>
    <div class="skills">
        <span class="skill-tag">HTML</span>
        <span class="skill-tag">CSS</span>
        <span class="skill-tag">JavaScript</span>
    </div>
</div>
```

**Personalize seu card:**
- 🎨 Escolha um emoji diferente para o avatar
- ✏️ Escreva seu nome
- 💬 Adicione uma descrição sobre você
- 🏷️ Liste as tecnologias que você conhece ou quer aprender

### **Passo 5: Teste Localmente**

Antes de fazer commit, veja como ficou:

1. Abra o arquivo `index.html` no seu navegador
2. Verifique se seu card apareceu corretamente
3. Veja se não quebrou nada na página

### **Passo 6: Commit e Push**

Agora que seu card está pronto, vamos salvar as alterações:

```bash
git add index.html
git commit -m "Adiciona card de [Seu Nome]"
git push origin card-seunome
```

Exemplo:
```bash
git add index.html
git commit -m "Adiciona card de João Silva"
git push origin card-joao
```

### **Passo 7: Abra um Pull Request**

1. Vá até o seu fork no GitHub
2. Você verá uma mensagem sugerindo criar um Pull Request
3. Clique em **"Compare & pull request"**
4. Adicione um título descritivo: `Adiciona card de [Seu Nome]`
5. Na descrição, escreva algo como:
   ```
   ## Descrição
   Adicionando meu card de apresentação ao portfólio da turma!
   
   ## Checklist
   - [x] Adicionei meu card
   - [x] Testei localmente
   - [x] O código está funcionando
   ```
6. Clique em **"Create pull request"**


## 🎨 Ideias de Personalização

Quer deixar seu card ainda mais legal? Experimente:

### **Emojis Criativos para Avatar:**
- 👨‍💻 👩‍💻 (programador/a)
- 🎮 (gamer)
- 🎨 (designer)
- 🎵 (músico/a)
- 📚 (estudioso/a)
- 🚀 (visionário/a)
- 🤖 (tech lover)

### **Ideias de Skills:**
- Linguagens: Python, JavaScript, Java, C++
- Web: HTML, CSS, React, Node.js
- Outros: Git, GitHub, Linux, Excel
- Interesses: IA, Jogos, Web Design, Apps

## 🎉 Resultado Final

Após todos os Pull Requests serem aceitos, teremos uma página incrível com todos os cards da turma! 

Cada contribuição é importante e faz parte do aprendizado colaborativo. 

## 🏆 Créditos

Este projeto foi desenvolvido durante a **Oficina de Introdução ao Git & GitHub** como prática de colaboração e controle de versão.