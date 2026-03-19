# 📊 E-commerce Data Intelligence: SQL & Python Strategy

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-DuckDB-orange?style=for-the-badge&logo=databricks)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-ffffff?style=for-the-badge&logo=python)

## 📖 Visão Geral do Projeto
Este projeto simula uma análise de inteligência de negócios para uma operação de e-commerce, transformando dados transacionais brutos em **insights estratégicos**. O foco principal é otimizar a tomada de decisão em áreas como Logística, Marketing e CRM.

Como profissional em transição para a área de **Dados**, utilizei este desafio para aplicar técnicas avançadas de manipulação de dados e visualização focada em UX (User Experience).

## 🎯 Objetivos de Negócio (KPIs)
A análise foi estruturada para responder a 8 perguntas críticas:
1. **Integridade Financeira:** Cálculo do faturamento real (Quantidade x Preço).
2. **Performance Regional:** Top 5 cidades com maior faturamento acumulado.
3. **Mix de Produtos:** Identificação de produtos com alto giro vs. alta margem.
4. **Eficiência de Venda:** Cálculo do **Ticket Médio** por transação.
5. **Fidelização (CRM):** Segmentação de Clientes VIP (gastos > R$ 500).
6. **Inteligência Logística:** Mapeamento do "Best-Seller" individual por cidade.

## 🛠️ Stack Tecnológica & Técnicas
* **Engine de Dados:** `DuckDB` (Processamento analítico de alta performance).
* **Linguagem:** `Python 3.12`.
* **Visualização:** `Matplotlib` (Gráficos horizontais com Data Labels e Cards de KPI).
* **SQL Avançado:** * **Window Functions** (`RANK() OVER PARTITION BY`) para rankings regionais.
    * **CTEs** e **Subqueries** para métricas agregadas complexas.
    * **Joins Triplos** para consolidação de Clientes, Pedidos e Produtos.

## 📈 Insights Extraídos
* **Decisões Logísticas:** Identificamos que cada cidade possui uma "âncora de consumo" diferente (ex: Birmingham foca em Eletros, enquanto Londres foca em Beleza), permitindo a otimização de estoque regionalizado.
* **Estratégia de Marketing:** A identificação de Clientes VIP permite a criação de campanhas de retenção com ROI muito superior à aquisição de novos leads.
* **Ticket Médio:** O monitoramento do valor médio por pedido serve como balizador para estratégias de "Frete Grátis".

## 🚀 Como Executar
1. Clone o repositório.
2. Certifique-se de ter as bibliotecas instaladas: `pip install pandas duckdb matplotlib`.
3. Abra o arquivo `.ipynb` no Jupyter Notebook ou VS Code.

---
**Desenvolvido por Douglas de Jesus Vittori** *Gestor de TI | Cientista de Dados em Formação* [LinkedIn](https://www.linkedin.com/in/douglasvittori/) | [Portfólio](https://douglasvittori-portfolio.lovable.app/)
