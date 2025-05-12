# **Crypto Prediction** <a href="https://skillicons.dev"> <img width="90px" align="right" src="https://skillicons.dev/icons?i=python,tensorflow" /> </a>

Uma aplicação de aprendizado de máquina para prever preços de criptomoedas, desenvolvida em Python usando bibliotecas populares como `tensorflow`, `pandas` e `matplotlib`. O programa analisa dados históricos de preços, treina uma rede neural LSTM e gera previsões gráficas, permitindo que usuários visualizem tendências futuras de preços.

---

## **Funcionalidades**

- **Extração de Dados** automatizada a partir do Yahoo Finance para pares de criptomoedas e moedas fiduciárias.
- **Processamento de Dados** com normalização via `MinMaxScaler` para preparar conjuntos de treino e teste.
- **Modelo de Rede Neural** com camadas LSTM para capturar padrões temporais nos preços.
- **Visualização Gráfica** comparando preços reais e preditos de forma intuitiva.

---

## **Pré-requisitos**

- Python 3.8 ou superior

Instale as dependências necessárias com o comando:

```bash
pip install numpy matplotlib pandas pandas_datareader scikit-learn tensorflow
