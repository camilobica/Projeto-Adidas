# Dicionário de Dados - Análise de Vendas Adidas

## Variáveis Categóricas
- `Retailer` *(category)* – Nome do varejista que realizou a venda.
- `Region` *(category)* – Região geográfica onde a venda ocorreu.
- `State` *(category)* – Estado onde a venda foi registrada.
- `City` *(category)* – Cidade onde a venda foi registrada.
- `Product` *(category)* – Tipo de produto vendido.
- `Sales Method` *(category)* – Método de venda utilizado (In-store, Online, Outlet).

## Variáveis Numéricas
- `Price per Unit` *(int32)* – Preço unitário do produto vendido.
- `Units Sold` *(float64)* – Quantidade de unidades vendidas.
- `Total Sales` *(float64)* – Valor total das vendas (faturamento).
- `Operating Profit` *(float64)* – Lucro operacional gerado pela venda.
- `Operating Margin` *(float64)* – Margem operacional da venda, calculada como `Operating Profit / Total Sales`.

## Variáveis Transformadas (Log)
- `Log_Total_Sales` *(float64)* – Logaritmo do valor total de vendas, para suavizar a escala e reduzir a dispersão.
- `Log_Units_Sold` *(float64)* – Logaritmo das unidades vendidas, para normalizar a distribuição.
- `Log_Operating_Profit` *(float64)* – Logaritmo do lucro operacional, para ajuste estatístico.
- `Log_Operating_Margin` *(float64)* – Logaritmo da margem operacional, para análise da distribuição.
- `Log_Price_per_Unit` *(float64)* – Logaritmo do preço unitário, para suavizar variações.

## Variáveis Temporais
- `Ano` *(int32)* – Ano da venda (2020 ou 2021).
- `Mês` *(int32)* – Mês da venda (1 a 12).