# Estrutura de Dados — UFCI-MG

Repositório de estudos das disciplinas **Estrutura de Dados** e **Laboratório de
Estrutura de Dados** do curso de **Engenharia de Computação** da
**UFCI-MG — Campus III (Leopoldina)**.

> Primeiro contato da carreira com estrutura de dados.
> Linguagem: **C**

Este repositório é apenas uma vitrine do material produzido ao longo da
disciplina: atividades avaliativas, TADs implementados do zero, exercícios de
treino e anotações.

### Nota sobre o nome da instituição

A instituição se chama atualmente **Universidade Federal de Ciência e Inovação de
Minas Gerais (UFCI-MG)**. Até 25 de setembro de 2026 era o **Centro Federal de
Educação Tecnológica de Minas Gerais (CEFET-MG)**, quando foi sancionado o
Projeto de Lei 4.952/2026, que transformou o CEFET-MG em universidade
([fonte](https://www.leopoldina.cefetmg.br/2026/10/01/25-09-2026-cefet-mg-agora-e-universidade-federal-de-ciencia-e-inovacao-ufci-mg/)).

Além do nome, a instituição passou a ter estrutura universitária (reitoria e
Conselho Universitário). Para os estudantes, porém, nada muda no essencial:
todos os cursos do antigo CEFET-MG continuam sendo oferecidos pela UFCI-MG, e
os estudantes e servidores (incluindo o corpo docente) passam a compor a
comunidade acadêmica da nova universidade.

Por isso os planos de disciplina em `docs/`, bem como os enunciados das
atividades em `pdfs_imagens_atividades/`, ainda trazem o nome antigo
(CEFET-MG). O conteúdo segue válido.

---

## Sobre as disciplinas

| | Estrutura de Dados | Laboratório de Estrutura de Dados |
|---|---|---|
| **Período** | 2º | 2º |
| **Eixo** | Fundamentos de Engenharia de Computação | Fundamentos de Engenharia de Computação |
| **Natureza** | Teórica / Obrigatória | Prática / Obrigatória |
| **Área de formação (DCN)** | Básica | Básica |
| **Carga horária** | 30 h-aula de teoria + 30 de prática (25 h) | 30 h-aula de prática (25 h) |
| **Pré-requisitos** | Programação de Computadores I; Laboratório de Programação de Computadores I | Não há |
| **Co-requisitos** | Não há | Estrutura de Dados |
| **Plano de disciplina** | [📄 PDF](docs/Estrutura-de-Dados.pdf) | [📄 PDF](docs/Laboratorio-de-Estrutura-de-Dados.pdf) |

### Ementa — Estrutura de Dados

- **Tipos abstratos de dados:** domínio de dados, características de TADs,
  programação com tipos abstratos de dados.
- **Representação linear de matrizes:** cálculo de endereçamento de elementos,
  matrizes esparsas, triangulares, diagonais e tridiagonais.
- **Listas lineares:** definição, operações mais comuns, representações de
  listas, listas contíguas, encadeadas, duplamente encadeadas, circulares e com
  descritor; listas ordenadas e busca binária; aplicações.
- **Pilhas e filas:** definição, operações básicas, implementação e aplicações.
- **Árvores:** definição, representações gráficas e em árvores, árvores
  binárias, árvores gerais como árvores binárias, caminhamentos em profundidade
  e em largura, árvore binária de busca e aplicações (avaliação de expressões,
  árvores de busca).
- **Filas de prioridades:** fundamentos; heaps (inserção, remoção e seleção de
  valores com maior prioridade), heaps binárias e representação vetorial.
- **Grafos:** definição, implementação por matrizes de adjacência, listas de
  adjacências e matrizes de incidências, representação de grafos direcionados e
  não-direcionados, aplicações.

### Ementa — Laboratório de Estrutura de Dados

Práticas em laboratório dos temas e tópicos abordados na disciplina
"Estrutura de Dados".

---

## Organização do repositório

| Pasta | Conteúdo |
|---|---|
| `tad/` | TADs implementados ao longo do curso: listas (sequencial, encadeada, ordenada, circular), pilha, filas, ABB, max-heap, grafos (matriz e lista de adjacência) e ponto. |
| `AI1_2_guilherme_carneiro_avellar/` | Atividade avaliativa 1 — questões 1 a 5. |
| `AI2_2_guilherme_carneiro_avellar/` | Atividade avaliativa 2. |
| `AI3_2_guilherme_carneiro_avellar/` | Atividade avaliativa 3 — listas sequenciais, encadeadas e circulares. |
| `guilherme_carneiro_avellar_AI3/` | Versão anterior da atividade avaliativa 3. |
| `AI4_guilherme_carneiro_avellar/` | Atividade avaliativa 4 — heap. |
| `AI4_2_guilherme_carneiro_avellar/` | Atividade avaliativa 4 (segunda versão) — ABB, fila encadeada e min-heap. |
| `AI5_guilherme_carneiro_avellar/` | Atividade avaliativa 5 — listas encadeadas. |
| `Guilherme/` | Pasta de trabalho consolidando TADs e atividades. |
| `exerciciosAleatorios/` | Exercícios livres, com destaque para grafos (matriz de adjacência, lista de adjacência, conjunto de arestas) e o problema do aeroporto. |
| `testes_avaliacoes/` | Testes e rascunhos de avaliações. |
| `treino_safadeus/` | Treinos rápidos (recursão, `calloc`, vetores). |
| `pdfs_imagens_atividades/` | Enunciados das atividades em PDF e imagens de apoio sobre `struct`, `typedef` e arrays. |
| `docs/` | Planos de disciplina em PDF (`Estrutura-de-Dados.pdf` e `Laboratorio-de-Estrutura-de-Dados.pdf`). |

---

## Como compilar

Os programas são escritos em C puro e compilam com `gcc`:

```bash
gcc -o programa main.c lista_enc.c -Wall
./programa
```

---

## Bibliografia

### Básica

- CORMEN, T. H.; LEISERSON, C. E.; RIVEST, R. L.; STEIN, C. **Algoritmos: Teoria e Prática.** Tradução da 2ª edição americana. 2002.
- ZIVIANI, N. **Projeto de Algoritmos com Implementações em C++ e Java.** São Paulo, 2007.
- ZIVIANI, N. **Projeto de Algoritmos com Implementações em Pascal e C.** 2. ed. São Paulo, 2004.

### Complementar

- HOROWITZ, E. **Fundamentos de Estruturas de Dados.** Rio de Janeiro, 1987.
- KNUTH, D. E. **The Art of Computer Programming**, vols. 1 e 3. 1998.
- MANBER, U. **Introduction to Algorithms: A Creative Approach.** Massachusetts, 1989.
- SEDGEWICK, R. **Algorithms in C.** 3. ed. 1998.
- SEDGEWICK, R. **Algorithms in C++, Parts 1–4.** 3. ed. 2002.

---

**Autor:** Guilherme Carneiro Avellar — Engenharia de Computação, UFCI-MG (ex-CEFET-MG), Campus III (Leopoldina).
