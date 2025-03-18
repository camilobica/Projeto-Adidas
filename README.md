# Análise de Dados - ADIDAS

Este projeto analisa o desempenho de vendas da Adidas nos anos de 2020 e 2021, com foco em identificar tendências de consumo e os impactos da pandemia de COVID-19 no varejo.

A crise sanitária de 2020 afetou significativamente o comportamento dos consumidores e a operação das empresas. No primeiro semestre, restrições e fechamentos de lojas físicas reduziram as vendas presenciais, enquanto as compras online ganharam força. O objetivo deste estudo é compreender essas mudanças e avaliar como as vendas evoluíram ao longo do período.

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
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
├── notebooks          <- Jupyter Notebook.
|
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── config.py    <- Configurações básicas do projeto.
|      └── estatistica.py  <- Funções criadas especificamente para este projeto.
|
├── referencias        <- Dicionários de dados.
|
├── imagens            <- Gráficos e figuras gerados para serem usados em relatórios
```

## Configuração do ambiente

1. Faça o clone do repositório que será criado a partir deste modelo.

    ```bash
    git clone ENDERECO_DO_REPOSITORIO
    ```

2. Crie um ambiente virtual para o seu projeto utilizando o gerenciador de ambientes de sua preferência.

    ```bash
    conda env export > ambiente.yml
    ```

## Um pouco mais sobre a base

[Clique aqui](referenciais/dicionario_de_dados.md) para ver o dicionário de dados da base utilizada.