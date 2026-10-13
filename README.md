# 7600105 - Física Básica 1

Anotações em LaTeX e códigos de computação científica em Python e Maple (com geração de código Fortran pelo Maple) da disciplina **7600105 - Física Básica 1**.

<p align="center">
  <img alt="Disciplina" src="https://img.shields.io/badge/7600105-F%C3%ADsica%20B%C3%A1sica%201-blue?style=for-the-badge">
  <img alt="Instituição" src="https://img.shields.io/badge/USP-Universidade%20de%20S%C3%A3o%20Paulo-orange?style=for-the-badge">
</p>

> **Disciplina:** 7600105 - Física Básica 1 <br>
> **Professor(a):** Esmerindo de Sousa Bernardes <br>
> **Instituição:** USP - Universidade de São Paulo

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX" />
  <img src="https://img.shields.io/badge/Maple-FF6600?style=for-the-badge" alt="Maple" />
</p>

## Requisitos

- **Python 3**
- Distribuição **LaTeX** (para compilar os `.tex`)
- **Maple** (para abrir os arquivos `.mw`; o código Fortran é gerado pelo próprio Maple)

## Como Executar

Scripts Python:

```bash
python ExercPython/ex1.py
```

Anotações LaTeX:

```bash
pdflatex Tarefas/tarefa1.tex
```

## Estrutura do Projeto

- `/ExercPython`: exercícios em Python (`ex1.py` a `ex3.py`).
- `/Plot`: gráficos em Python (`Plot/Python`) e em Maple (`Plot/Maple`).
- `/Questionarios`: questionários por tema, em LaTeX com códigos de apoio em Python e Maple:
  - `01_introducao`, `02_revgeometria`, `03_derivadas`, `04_energia`, `05_gravitacao`.
- `/Tarefas`: tarefas em LaTeX (`tarefa1.tex`) e em HTML.
