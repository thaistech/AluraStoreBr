# 🛍️ Alura Store – Análise de Vendas

Este projeto é uma análise exploratória de dados (EDA) baseada em um desafio do curso de Data Science da Alura. Utilizamos dados de vendas de quatro lojas fictícias para identificar padrões de consumo, produtos mais vendidos, desempenho por categoria, avaliações dos clientes e custos logísticos (frete).

---

## 🎯 Propósito da Análise

O objetivo deste projeto foi:

- Analisar o desempenho das quatro lojas em termos de faturamento, avaliação dos clientes e frete.
- Descobrir quais categorias e produtos geram mais receita.
- Obter insights estratégicos para auxiliar na tomada de decisão (como identificar a loja com pior desempenho para possível venda ou reestruturação).

---

## 📁 Estrutura do Projeto

alura-store/ ├── data/ # Dados CSV das 4 lojas (carregados via URL) ├── AluraStore_Analise.ipynb # Notebook principal com a análise ├── README.md # Este arquivo ├── imagens/ # Capturas de gráficos (opcional)



---

## 📊 Exemplos de Gráficos e Insights

### 💰 Faturamento Total por Loja
Gráfico de barras representando o faturamento total individual:

- Loja 1: R$ 1.534.509
- Loja 2: R$ 1.488.459
- Loja 3: R$ 1.464.025
- Loja 4: **R$ 1.384.498** (menor faturamento)

### 📦 Vendas por Categoria
Gráfico mostra que **Móveis** é a categoria mais vendida, seguido de **Eletrônicos** e **Brinquedos**.

### ⭐ Avaliação Média das Lojas
- Loja 3 lidera com 4.05 estrelas, seguida da Loja 2 (4.04).
- Loja 4 tem desempenho mediano (4.00).

### 🔥 Produto mais vendido
- **Cômoda** (da categoria Móveis)

### ❄️ Produto menos vendido
- **Celular ABXY** (possivelmente por preço ou avaliação ruim)

### 🚚 Frete Médio por Loja
- Loja 4 tem o menor frete médio (R$ 31,28), mas isso **não reflete em melhor desempenho nas vendas**.

---

## ✅ Conclusão Estratégica

> A loja com **pior desempenho geral** foi a **Loja 4**, sendo recomendada para venda ou reestruturação. Ela teve o menor faturamento, avaliação apenas média e não liderou em nenhuma métrica além do frete.



