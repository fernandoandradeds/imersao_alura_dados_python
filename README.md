# Dashboard de Salários na Área de Dados

Dashboard interativo desenvolvido com **Streamlit** e **Plotly** para análise de salários de profissionais de dados no Brasil e no mundo. Projeto desenvolvido durante a **Imersão Python + Dados** da Alura.

## Funcionalidades

- Filtros por ano, senioridade, tipo de contrato e tamanho da empresa
- KPIs: salário médio, salário máximo, total de registros, cargo mais frequente
- **Top 10 cargos** por salário médio (horizontal bar chart)
- **Distribuição de salários** por faixa (histograma)
- **Proporção por tipo de trabalho** (presencial/remoto/híbrido — donut chart)
- **Mapa choropleth** com salário médio de Cientistas de Dados por país

## Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Como executar

```bash
git clone https://github.com/fernandoandradeds/imersao_alura_dados_python.git
cd imersao_alura_dados_python

pip install -r requirements.txt
streamlit run app.py
```

## Estrutura

```
imersao_alura_dados_python/
├── app.py                   # Dashboard Streamlit
├── aulas.ipynb              # Notebooks das aulas da imersão
├── dados-imersao-final.csv  # Dataset local
└── requirements.txt
```

## Conteúdo dos notebooks

O arquivo `aulas.ipynb` contém as análises desenvolvidas ao longo da imersão:
- Análise exploratória de dados com Pandas
- Visualizações com Matplotlib e Seaborn
- Introdução a Machine Learning aplicada a dados salariais

## Autor

**Fernando Andrade** — [GitHub](https://github.com/fernandoandradeds) · [LinkedIn](https://www.linkedin.com/in/fernandoandradeds/)
