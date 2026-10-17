# Guia Básico de Comandos Git

Página de consulta rápida com os principais comandos do Git, explicados em português e prontos para copiar com um clique. Feita para quem está começando e quer salvar versões do projeto e enviá-las ao GitHub sem complicação.

---

## O que tem no site

- **18 comandos** explicados de forma simples, cada um com descrição e, quando útil, um exemplo de uso
- **Botão "Copiar"** em cada comando, com aviso na tela quando a cópia é feita
- **Filtros por categoria** para encontrar o comando mais rápido
- **Seção "Como usar o Git no dia a dia"** com a sequência mais comum: `git add .`, `git commit` e `git push`
- **Tema escuro** inspirado no visual do GitHub
- **Layout responsivo**, que funciona bem no computador e no celular

---

## Categorias

| Categoria | Comandos |
|---|---|
| Começar e configurar | `git init`, `git clone`, `git config` (nome e e-mail) |
| Salvar alterações | `git status`, `git add`, `git commit` |
| GitHub | `git remote add origin`, `git push`, `git pull`, `git remote -v` |
| Branches | `git branch`, `git switch -c`, `git switch` |
| Histórico | `git log --oneline`, `git diff` |

---

## Estrutura do projeto

O projeto é um único arquivo HTML, com o CSS e o JavaScript dentro dele. Não depende de bibliotecas externas nem de internet para funcionar.

```
guia-git/
└── index.html    # Estrutura, estilos e interatividade (filtros e botão de copiar)
