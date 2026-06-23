# MiniProjeto DataView 

## Sobre o projeto 
O DataView PY é um projeto de análise exploratória de dados (EDA) de vendas do banco de dados "US Superstore data" retirado do site "https://www.kaggle.com/datasets/juhi1994/superstore/data", 
desenvolvido em Python em um notebook do colab. O notebook lê, limpa, transforma, 
analisa e visualiza um dataset de vendas, gerando métricas e insights. 
## O que o projeto analisa - Receita total e volume de vendas por mês - Top produtos e categorias por receita - Desempenho por estado "EUA"- Segmentação de clientes por nível de gasto (Bronze, Prata, Ouro) - Comparação entre os dados com e sem tratamento de outliers (v1 e v2) - Exportação de relatórios em CSV e JSON 
## Objetivo 
Praticar os principais conceitos: - Lógica de programação com Python - Variáveis, tipos de dados e operadores - Condicionais (if, elif, else) e repetição (for, while) - Funções com parâmetros, retorno e funções lambda - Funções reutilizáveis - Leitura e escrita de arquivos CSV e JSON - Módulo datetime para manipulação de datas - Expressões regulares com o módulo re - Pandas: DataFrames, limpeza, groupby, filtros e transformações - NumPy: arrays, operações vetorizadas, broadcasting - Detecção e tratamento de outliers (IQR ou z-score) - Matplotlib e Seaborn: gráficos, customização e exportação em PNG - Uso básico do GitHub 
## Como executar 
### No Google Colab (recomendado) 
1. Faça upload do notebook dataview.ipynb 
2. Abra o arquivo carregado no Colab 
3. Execute as células na ordem, de cima para baixo 
30 
Atualizado em 
### Localmente com VS Code 
1. Instale o Python 3.10+ e o VS Code. 
2. Instale as dependências: 
pip install pandas numpy matplotlib seaborn 
## Estrutura do projeto 
projeto/ 
|-- data/ 
|   
|-- raw/                     
|   
|   
|   
|   
|-- processed/ 
|   
|   
|-- v1_com_outliers/  
|-- final/                   
# Dataset bruto gerado/baixado 
5 de jun. de 2026
Criado por: xxx 
# Dados de limpeza geral, outliers mantidos 
|-- v2_outliers_tratado/ # Limpeza v1 + tratamento de outliers 
# Dataset escolhido para uso futuro 
|-- notebooks/ 
|   
|-- dataview.ipynb           
|-- outputs/ 
|   
|-- metricas_por_mes.csv 
|   
|   
|   
|-- segmentacao_clientes.csv 
|-- estatisticas_gerais.json 
|-- graficos/ 
|-- README.md 
## Ferramentas utilizadas - Python 3.10+ 
# Notebook principal de EDA - Google Colab / VS Code - Bibliotecas: pandas, numpy, matplotlib, seaborn, re, datetime, os, random - GitHub para versionamento 
## Vídeo de demonstração 
[Inserir link do Google Drive ou YouTube aqui] 
