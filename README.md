# 📊 Painel de Vendas – Power BI

Dashboard de análise de vendas de uma loja fictícia (**Casa Conforto**), desenvolvido em Power BI para praticar ETL, modelagem de dados e criação de medidas em DAX.

## 🎯 Objetivo
Acompanhar o desempenho comercial e responder perguntas como:
- Quanto estamos faturando e qual a margem de lucro?
- Quais produtos e categorias mais vendem?
- Qual o desempenho de cada vendedor e região?
- Como a receita evolui em relação ao mês e ao ano anteriores?
- Qual canal de venda traz mais resultado?

## 🖼️ Visão geral do painel
| Elemento | Descrição |
|---|---|
| Cartões (KPIs) | Receita Total, Lucro Bruto, Margem %, Ticket Médio e Nº de Vendas |
| Gráfico de linhas | Receita Total x Receita do Ano Anterior |
| Gráfico de colunas | Receita por Produto e Categoria |
| Gráfico de colunas | Vendas por Canal ao longo do tempo |
| Mapa | Receita por Região |
| Segmentações | Período, Vendedor e Categoria |

![Painel de vendas]()

## 🗂️ Modelo de dados
Modelo em estrela, com a tabela fato **Vendas** ligada às dimensões **Produtos**, **Clientes**, **Vendedores** e **Calendário**.

## 🧮 Principais medidas DAX
- `Receita Total`, `Custo Total`, `Lucro Bruto`, `Margem %`
- `Ticket Médio`, `Clientes Ativos`, `Receita por Cliente`
- `Var. Mensal %` e `Var. Anual %` (inteligência de tempo)
- `Ranking Produto` e `Ranking Vendedor` (RANKX)
- `% do total` e `Clientes novos`

## 🛠️ Ferramentas
Power BI Desktop (formato PBIP) · Power Query · DAX · Excel (fonte de dados)

## 👤 Autor

**Kayky Pramos**

- GitHub: [@KaykyPramoshttps](https://github.com/KaykyPramoshttps)
- LinkedIn: [Kayky Pereira Ramos](https://www.linkedin.com/in/kayky-pereira-ramos-180770274)

