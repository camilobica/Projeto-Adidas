# Análise de Dados - ADIDAS

Este projeto analisa o desempenho de vendas da Adidas nos anos de 2020 e 2021, com foco em identificar tendências de consumo e os impactos da pandemia de COVID-19 no varejo.

A crise sanitária de 2020 afetou significativamente o comportamento dos consumidores e a operação das empresas. No primeiro semestre, restrições e fechamentos de lojas físicas reduziram as vendas presenciais, enquanto as compras online ganharam força. O objetivo deste estudo é compreender essas mudanças e avaliar como as vendas evoluíram ao longo do período.

![imagem](imagens/tenis_adidas.jpg)

## Etapas do Projeto

1. **Importação de Dados**: Carregamento e pré-processamento dos dados.
2. **Tratamento de Dados**: Limpeza e organização para análise
3. **Análise Exploratória de Dados (EDA)**: Visualização e identificação de padrões
4. **Análise Descritiva (Estatística)**: Estatísticas e testes para validar hipóteses

Os dados foram obtidos no Kaggle e estão armazenados em um arquivo Excel, contendo informações detalhadas sobre vendas da Adidas.

## Ferramentas Utilizadas

- **Pandas e Numpy**: Manipulação e tratamento dos dados.
- **Seaborn e Matplotlib**: Visualização gráfica.
- **Scipy**: Testes estatísticos e análises avançadas.
- **Cycler**: Personalização de cores nos gráficos.
- **Scikit-learn (sklearn.preprocessing)** – Padronização e normalização dos dados para modelagem estatística e machine learning.  

## Organização do projeto

```
├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente_projeto_adidas.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
├── notebooks          <- Jupyter Notebook.
|
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      └── estatistica.py  <- Funções criadas especificamente para este projeto.
|
├── referencias        <- Dicionários de dados.
|
├── imagens            <- Gráficos e figuras gerados para serem usados em relatórios
```

## Configuração do ambiente

1. Faça o clone do repositório.

    ```bash
    git clone git@github.com:camilobica/Projeto-Adidas.git
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o `conda`.

    ```bash
    conda env create -f ambiente_projeto_adidas.yml --name estatistica
    ```

## Um pouco mais sobre a base

[Clique aqui](referenciais/dicionario_de_dados.md) para ver o dicionário de dados da base utilizada.

## Resumo dos princiapis resultados

### 1️⃣ Expansão do Mercado
- O número de estados e cidades com vendas aumentou significativamente de **9 para 46 estados** e **9 para 45 cidades** entre 2020 e 2021.
- Isso indica uma **expansão geográfica** e maior presença da Adidas no mercado.

### 2️⃣ Mudança no Perfil dos Produtos Mais Vendidos
- Em 2020, o produto mais vendido foi **Men's Street Footwear**.
- Em 2021, o destaque foi **Men’s Athletic Footwear**, sugerindo um **aumento no interesse por produtos esportivos**, possivelmente relacionado à maior preocupação com a saúde e bem-estar.

### 3️⃣ Alteração nos Canais de Venda
- Em 2020, a maioria das vendas ocorreu via **Outlets (46.2%)**.
- Em 2021, houve uma grande mudança, com **vendas online** superando os outros canais, representando **42.2% das transações**.
- O crescimento do comércio eletrônico reflete **mudanças no comportamento do consumidor**, possivelmente impulsionadas pela pandemia.

### 4️⃣ Análise de Faturamento e Volume de Vendas
- O total de unidades vendidas aumentou **quase 5x** de 2020 para 2021.
- O faturamento cresceu consideravelmente, com **valores mensais superando 70 milhões em dezembro de 2021**, em comparação com **máximos de 15 milhões em 2020**.
- A média de preços caiu em 2021, indicando possíveis ajustes estratégicos para impulsionar as vendas.

### 5️⃣ Correlação Entre Variáveis
- **O preço unitário** apresenta uma **correlação positiva** com o total de vendas (0.39), sugerindo que o aumento das vendas pode aumentar o valor médio do preço unitário de cada produto.
- A **margem operacional** apresenta uma **correlação negativa** com as unidades vendidas (-0.34), sugerindo que o aumento do volume pode reduzir a rentabilidade percentual.

### 6️⃣ Testes Estatísticos
- Os testes de **Qui-Quadrado** indicam que **há associação significativa** entre método de venda e varejistas, confirmando que diferentes varejistas utilizam estratégias distintas.
- Entretanto, **não há relação estatística significativa entre produto e região**, sugerindo que os produtos são distribuídos de forma relativamente uniforme entre os mercados.

---

## Conclusão
A análise revelou **mudanças estratégicas na operação da Adidas**, incluindo:

✅ **Expansão geográfica** e maior diversificação de vendas.  
✅ **Crescimento do e-commerce**, alterando o comportamento dos consumidores.  
✅ **Mudança no perfil dos produtos vendidos**, indicando novas tendências de consumo.  
✅ **Impacto do volume de vendas no faturamento**, mas com efeito sobre a margem operacional.  

Esses insights podem **orientar estratégias futuras de precificação, distribuição e marketing**, garantindo um crescimento sustentável da marca.
