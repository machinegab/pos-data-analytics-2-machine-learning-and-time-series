# pos-data-analytics-2-machine-learning-and-time-series
Pós graduação em Data Analytics: projeto de entrega da fase 2 sobre o tema de MACHINE LEARNING AND TIME SERIES

---

# Projeto: membro de um time de investimentos responsável pela criação de um modelo preditivo de dados da IBOVESPA.

Este repositório contém a solução desenvolvida pelo time de investimentos para a criação de um modelo preditivo focado nos dados de fechamento diário da IBOVESPA. O objetivo principal deste projeto foi utilizar técnicas avançadas de Machine Learning para prever os valores de fechamento, auxiliando na tomada de decisões estratégicas de investimento.

## Índice

- [Contexto do Projeto](#contexto-do-projeto)
- [Arquivos no Repositório](#arquivos-no-repositório)
- [Ferramentas e Tecnologias Utilizadas](#ferramentas-e-tecnologias-utilizadas)
- [Instruções para Execução](#instruções-para-execução)
- [Resultados e Conclusões](#resultados-e-conclusões)
- [Autores](#autores)

## Contexto do Projeto

Neste projeto realizamos a criação de diversos tipo de modelos preditivos, com o objetivo de desenvolver uma entrega satisfatória para os dados de fechamento diário do índice IBOVESPA. A solução entregue visa fornecer previsões precisas para suportar decisões de compra e venda de ativos, melhorando a eficiência e a lucratividade das operações financeiras.

Os modelos foram: Naive, SeasonalNaive, SeasonalWindowAverage, AutoARIMA, AutoETS e Prophet.

## Arquivos no Repositório

- `Tech Challenge Fase 2.ipynb`: O notebook contendo todo o processo de análise e criação dos diversos modelos utilizados.
- `Dados Históricos - Ibovespa.csv`: A base de dados utilizada para alimentar os códigos desenvolvidos
  
## Ferramentas e Tecnologias Utilizadas

- **Python**: Linguagem de programação principal utilizada no projeto.
- **Scikit-Learn**: Utilizado para a construção e avaliação dos modelos de Machine Learning.
- **Seaborn**: para criação de visualizações
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib/Seaborn**: Para a criação de gráficos e visualizações de dados.
- **Jupyter Notebook**: Ambiente utilizado para o desenvolvimento e execução do código.

## Instruções para Execução

1. Clone este repositório:
   ```
   git clone https://github.com/machinegab/pos-data-analytics-2-machine-learning-and-time-series.git
   ```
2. Navegue até o diretório do projeto:
   ```
   cd pos-data-analytics-2-machine-learning-and-time-series
   ```
3. Instale as dependências necessárias:
   ```
   pip install -r requirements.txt
   ```
4. Execute o notebook Jupyter para reproduzir as análises:
   ```
   jupyter notebook "Tech Challenge Fase 2.ipynb"
   ```

## Resultados e Conclusões

Neste projeto, testamos diversos modelos preditivos e justificamos as escolhas e os pontos positivos e negativos de cada um deles. 

Considerando tanto a precisão quanto os recursos utlizados por cada modelo, SeasonalWindowAverage é a melhor escolha. Ele oferece a melhor precisão entre todas as opções e, apesar de exigir mais recursos computacionais do que os modelos mais simples (Naive e SeasonalNaive), é menos exigente do que AutoARIMA, AutoETS e Prophet.

## Autores

- **Gabriel Martins** - [gabrielm54@icloud.com](mailto:gabrielm54@icloud.com)
- **Danilo Pires** - [danilo.pires01@gmail.com](mailto:danilo.pires01@gmail.com)
