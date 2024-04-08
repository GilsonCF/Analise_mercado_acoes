# Análise de Séries Temporais do Índice Bovespa
Este projeto realiza uma análise de séries temporais do Índice Bovespa (Ibovespa) utilizando dados históricos obtidos do Yahoo Finance. Ele inclui o uso das bibliotecas Pandas, Matplotlib, Statsmodels e yfinance para baixar os dados, fazer a decomposição sazonal e visualizar os resultados.

## Descrição
O script Python analise_ibovespa.py baixa os dados históricos do Índice Bovespa (Ibovespa) usando a biblioteca yfinance, realiza a decomposição sazonal da série temporal usando a função seasonal_decompose da biblioteca Statsmodels e visualiza os resultados usando Matplotlib.

## Requisitos
Python 3.x
Pandas
Matplotlib
Statsmodels
yfinance
## Uso
Clone este repositório em sua máquina local.
Instale as dependências necessárias executando pip install -r requirements.txt.
Execute o script Python analise_ibovespa.py.
O script baixará os dados históricos do Índice Bovespa, fará a decomposição sazonal e plotará os resultados.
## Exemplo de Saída
O gráfico resultante mostra a série temporal observada, a tendência e outros componentes da decomposição sazonal.
