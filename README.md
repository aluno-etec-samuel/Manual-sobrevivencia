# Manual de Utilização do Repositório

## Criando o repositório local

Inicialize o Git na pasta do projeto:

```bash
git init
```

Adicione todos os arquivos:

```bash
git add .
```

Crie o primeiro commit:

```bash
git commit -m "Primeiro commit"
```

Crie a branch `develop`:

```bash
git branch -M develop
```

Conecte o repositório local ao GitHub:

```bash
git remote add origin https://github.com/aluno-etec-samuel/Manual-sobrevivencia.git
```

Envie o projeto para o GitHub:

```bash
git push -u origin develop
```

---

## Para os integrantes do grupo

Clone o repositório:

```bash
git clone https://github.com/aluno-etec-samuel/Manual-sobrevivencia.git
```

Entre na pasta do projeto:

```bash
cd Manual-sobrevivencia
```

Troque para a branch `develop`:

```bash
git checkout develop
```

Antes de começar a editar, atualize o projeto:

```bash
git pull origin develop
```

Depois de fazer alterações:

```bash
git add .
git commit -m "Descrição da alteração"
git push origin develop
```