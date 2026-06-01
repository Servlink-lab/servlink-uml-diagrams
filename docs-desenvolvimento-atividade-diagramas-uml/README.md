# Documentação de desenvolvimento — Atividade Diagramas UML

Materiais de referência e do projeto ServLink usados para elaborar a modelagem UML (PMI II). Arquivos binários (PDF/DOCX) estão versionados com **Git LFS** para visualização no GitHub.

## Estrutura

| Pasta | Conteúdo |
|-------|----------|
| `referencias-pmi/` | Modelos e exemplos da disciplina (Rational Rose, descritivo de use case, checklist dos 9 diagramas) |
| `projeto-servlink/` | ERS (template PMI II) e modelagem UML apresentada em aula (base do `index.html`) |

## Arquivos em `referencias-pmi/`

- **Apostila UML - Rational Rose.pdf** — notação e diagramas UML
- **Exemplo Modelagem e Descrição Use-case (1).pdf** — exemplo de RF + casos de uso com include/extend
- **Modelo de Descritivo de Use-Case (1).pdf** — template de fluxos (ator, pré/pós-condições, exceções)
- **Modelos dos Diagramas UML para entrega da Documentação PMI III (1).docx** — modelo de referência com checklist dos 9 diagramas (nome do arquivo menciona PMI III)

## Arquivos em `projeto-servlink/`

- **Documento de Especificação de Requisitos de Software (ERS) - PMI II.docx.pdf** — estrutura de requisitos (PMI II)
- **Modelagem UML - Servlink (desatualizado) - apresentado em aula.pdf** — versão em slides/PDF da modelagem ServLink

## Entrega interativa

Diagramas consolidados em HTML (GitHub Pages): [index.html](../index.html) · **https://servlink-lab.github.io/servlink-uml-diagrams/**

## Git LFS

No clone, após `git clone`, execute:

```bash
git lfs install
git lfs pull
```

Sem LFS, os PDFs aparecem como ponteiros de texto no GitHub.
