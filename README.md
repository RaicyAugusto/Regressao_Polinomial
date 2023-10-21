# Regressão Polinomial

![Python](https://img.shields.io/badge/-Python-blue)
![Jupyter Notebook](https://img.shields.io/badge/-Jupyter%20Notebook-orange)


Este exercício visa prever se o salário de um candidato está de acordo com suas expectativas. Suponha que o candidato tenha atuado como Gerente Regional, com uma pretensão salarial de $160.000, e possua 2 anos de experiência nessa função. Para verificar se o salário solicitado está em linha com sua experiência anterior, foi realizado um modelo básico utilizando regressão polinomial.

## Dependências

Este projeto requer as seguintes bibliotecas:

- Pandas
- Numpy
- Matplotlib

Certifique-se de tê-las instaladas antes de executar o script.

## Instruções de Uso

1. Clone este repositório em sua máquina local.
2. Verifique se o conjunto de dados 'Position_Salaries.csv' está localizado no mesmo diretório do script.
3. Execute o código fornecido em um ambiente compatível com Python.

## Passos no Código

1. **Importando as bibliotecas:** As bibliotecas necessárias, como Pandas, NumPy e Matplotlib, são importadas no início do script.

2. **Importando e preparando os dados:** O conjunto de dados 'Position_Salaries.csv' é importado e preparado para análise.

3. **Treinando o modelo de regressão linear:** O modelo de regressão linear é treinado utilizando a biblioteca scikit-learn.

4. **Treinando o modelo de regressão polinomial:** O modelo de regressão polinomial é treinado utilizando a biblioteca scikit-learn, com uma transformação polinomial de grau 4.

5. **Visualizando os resultados:** Os resultados da regressão linear e polinomial são visualizados utilizando gráficos do Matplotlib.

6. **Prevendo novos resultados:** Previsões para novos candidatos são feitas utilizando os modelos treinados.

Certifique-se de que o arquivo 'Position_Salaries.csv' esteja formatado corretamente e de que o script seja executado em um ambiente compatível com Python.
