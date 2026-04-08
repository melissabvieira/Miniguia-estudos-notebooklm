## 📘 Miniguia de Estudos: Comandos Git no Terminal

### 🎯 Objetivo

Este projeto tem como objetivo criar um guia prático de comandos Git utilizando Inteligência Artificial como apoio no aprendizado. 
A proposta é compreender os principais comandos utilizados no dia a dia e ter um material de consulta rápida.

---

### 📚 Fontes

- https://git-scm.com/docs  
- https://www.atlassian.com/git/tutorials  
- https://docs.github.com/pt  

---

### 🧠 Prompts Utilizados

- "Quais são os comandos básicos do Git para iniciantes?"  
- "Diferença entre git pull e git fetch"  
- "O que fazer em caso de conflitos durante um merge?"  

**Dificuldades encontradas:** respostas genéricas e falta de exemplos.  
**Solução:** solicitar explicações mais simples e com exemplos práticos.

---

## 📖 Miniguia de Comandos Git

### 🔹 Comandos Básicos

```bash
git init              # Inicia um repositório
git clone URL         # Clona um repositório remoto
git add .             # Adiciona arquivos para commit
git commit -m "msg"   # Salva as alterações
git push              # Envia para o repositório remoto
git pull              # Atualiza o repositório local
git status            # Mostra o status dos arquivos
git log               # Exibe o histórico de commits
```

---

### 🔹 Iniciando um Projeto

```bash
git init nome-projeto
git clone URL
```

- Use `git init` para criar um repositório do zero  
- Use `git clone` para copiar um projeto existente  

💡 Dica: sempre criar um `README.md` para documentar o projeto.

---

### 🔹 Ciclo de Trabalho

```bash
git status
git add arquivo
git commit -m "Informação do que foi realizado"
```

1. Verifica alterações  
2. Adiciona arquivos  
3. Salva no histórico  

---

### 🔹 Branches e Colaboração

```bash
git branch nome-branch
git checkout nome-branch
```

- Branch: permite trabalhar sem afetar o projeto principal  
- Pull Request: usado no GitHub para revisar alterações  

---

### 🔹 Sincronização

```bash
git pull
git push
git log
```

- `git pull`: atualiza seu projeto  
- `git push`: envia alterações  
- `git log`: consulta histórico  

---

### 🔹 Conflitos

Quando houver conflito:

- Abrir o arquivo  
- Remover:
```
<<<<<<<
=======
>>>>>>>
```
- Ajustar manualmente o conteúdo  

---

### 🔹 Dicas

- Usar GitHub Desktop para interface visual  
- Criar atalhos (aliases) para comandos  

---

## 🚀 Conclusão

Este projeto reforçou o uso da Inteligência Artificial como ferramenta de aprendizado, permitindo compreender melhor o Git e organizar um guia prático para uso no dia a dia.
