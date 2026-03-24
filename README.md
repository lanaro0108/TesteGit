# TesteGit

## Anotações da aula - 24/03

---

## Estrutura básica

```bash
echo "# nome_repositorio" >> README.md
git init
git add README.md
git commit -m "Mensagem"
git branch -M main
git remote add origin https://github.com/nome-usuario/nome_repositorio.git
git push -u origin main
```

---

## Comandos principais do Git

### Clonar repositório

```bash
git clone https://github.com/usuario/repositorio.git
```

---

### Verificar status

```bash
git status
```

---

### Adicionar arquivos

Adicionar um arquivo:

```bash
git add nome_do_arquivo
```

Adicionar todos:

```bash
git add .
```

---

### Criar commit

```bash
git commit -m "mensagem do commit"
```

---

### Enviar para o GitHub

```bash
git push
```

---

### Atualizar repositório local

```bash
git pull
```

---

### Histórico de commits

Completo:

```bash
git log
```

Resumido:

```bash
git log --oneline
```

---

### Trabalhar com branches

Criar branch:

```bash
git branch nome-branch
```

Trocar de branch:

```bash
git checkout nome-branch
```

Criar e trocar:

```bash
git checkout -b nome-branch
```

---

### Merge (mesclar branches)

```bash
git merge nome-branch
```

---

### Remover arquivo

```bash
git rm nome_arquivo
```

---

### Desfazer alterações

Antes do commit:

```bash
git checkout -- nome_arquivo
```

Desfazer último commit:

```bash
git reset --soft HEAD~1
```

---
