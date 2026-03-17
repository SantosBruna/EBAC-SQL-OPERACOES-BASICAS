# 🗄️ Módulo 25 – Operações Básicas SQL

Exercícios práticos do **Módulo 25** do programa [Profissão Cientista de Dados – EBAC](https://ebaconline.com.br/), com foco em consultas SQL utilizando **SQLite** integrado ao Python via **pandas**.

---

## 📋 Sobre o Módulo

Este módulo aprofunda as operações básicas de SQL aplicadas à ciência de dados, explorando filtragem, contagem, agregação e ordenação de dados em bancos de dados relacionais diretamente em um ambiente Python/Colab.

A base de dados utilizada simula uma tabela de vendas (`TB_VENDAS_TAREFA.csv`) com informações de compras, clientes, produtos, valores unitários e quantidades.

---

## 🧪 Exercícios

| # | Descrição | Conceitos Aplicados |
|---|-----------|---------------------|
| 1 | Retornar os nomes dos produtos distintos da base | `SELECT DISTINCT` |
| 2 | Contar os clientes distintos da base | `COUNT`, `DISTINCT`, `AS` |
| 3 | Retornar produtos distintos com valor unitário ≥ R$ 50 | `SELECT DISTINCT`, `WHERE` |
| 4 | 🏆 **Desafio:** Retornar as 5 compras com maior valor total gasto | Multiplicação de colunas, `AS`, `ORDER BY DESC`, `LIMIT` |
| 5 | Retornar produtos e a média do preço unitário, do maior para o menor | `AVG`, `GROUP BY`, `ORDER BY DESC` |
| 6 | Retornar os 3 clientes que mais realizaram compras | `COUNT`, `GROUP BY`, `ORDER BY DESC`, `LIMIT` |

---

## 💡 Principais Aprendizados

- **Valores únicos** com `SELECT DISTINCT` e `COUNT(DISTINCT)`
- **Filtragem de registros** com `WHERE` e operadores de comparação
- **Colunas calculadas** multiplicando campos diretamente no SQL
- **Funções de agregação** como `AVG()` e `COUNT()`
- **Agrupamento de dados** com `GROUP BY` para análises por categoria ou cliente
- **Ordenação e paginação** com `ORDER BY DESC` e `LIMIT`
- **Alias de colunas** com `AS` para nomear resultados
- **Integração SQL + Python**: uso do `sqlite3` e `pandas.read_sql_query()` para rodar queries no Colab

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- [pandas](https://pandas.pydata.org/)
- [SQLite3](https://docs.python.org/3/library/sqlite3.html)
- Google Colab

---

## 📁 Estrutura do Repositório

```
├── Profissao_Cientista_de_Dados_M25_PratiqueFEITO.ipynb
└── README.md
```

---

## 👩‍💻 Autora

**Bruna S. R. Santos**
* 🔗 LinkedIn: [www.linkedin.com/in/brunasrsantos](https://www.linkedin.com/in/brunasrsantos)
* 📧 Email: brunasrsantos@gmail.com

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License**.
