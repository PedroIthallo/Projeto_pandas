# 📊 Análise de Desempenho de Estudantes com Pandas

Projeto de **Análise Exploratória de Dados (EDA)** utilizando a biblioteca Pandas, focado no dataset **StudentsPerformance**.

---

## Sobre o Projeto

Este notebook demonstra as principais funcionalidades do **Pandas** através da análise de desempenho de 1.000 estudantes em provas de matemática, leitura e escrita.

O objetivo é mostrar de forma prática como explorar, limpar, transformar e analisar dados tabulares usando Python.

---

## Dataset

- **Nome do arquivo:** `StudentsPerformance.csv`
- **Quantidade de registros:** 1.000
- **Colunas:**

| Coluna                        | Descrição                                      |
|-------------------------------|------------------------------------------------|
| `gender`                      | Gênero do estudante                            |
| `race/ethnicity`              | Grupo étnico                                   |
| `parental level of education` | Nível de escolaridade dos pais                 |
| `lunch`                       | Tipo de almoço (standard / free/reduced)       |
| `test preparation course`     | Fez curso preparatório (none / completed)      |
| `math score`                  | Nota de Matemática (0-100)                     |
| `reading score`               | Nota de Leitura (0-100)                        |
| `writing score`               | Nota de Escrita (0-100)                        |

---

## Principais Análises Realizadas

- Carregamento e visualização inicial dos dados
- Verificação de duplicatas e valores ausentes
- Análise estatística descritiva (média, mediana, desvio padrão, etc.)
- Análise de valores únicos e frequência (ex: distribuição por gênero)
- Ordenação dos estudantes pelas melhores notas
- Criação da coluna `mean` (média geral das três provas)
- Filtros avançados (ex: estudantes masculinos com nota de matemática ≥ 70 que **não** fizeram curso preparatório)
- Agrupamento por gênero com cálculo de média e mediana das notas

---

## Tecnologias Utilizadas

- **Python 3.12**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
