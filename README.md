# 🍎 Análise de Dados e Computação Numérica com NumPy

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![License](https://img.shields.io/badge/License-MIT-green)

Este projeto consiste em um estudo aprofundado da biblioteca **NumPy**, aplicada à análise de séries temporais de preços de frutas (maçãs) em diversas cidades russas. O projeto foi desenvolvido como parte da formação em Data Science da Alura.

O objetivo principal foi ir além da manipulação básica de arrays, explorando conceitos matemáticos aplicados à programação, como álgebra linear e estatística para previsão de tendências.

## 🚀 O que foi desenvolvido?

Neste notebook, exploramos o ciclo completo de uma análise exploratória de dados numérica:

1.  **Ingestão de Dados (ETL):** Carregamento de datasets brutos (`apples_ts.csv`) diretamente de URLs externas.
2.  **Manipulação de Arrays:** Transposição, redimensionamento e indexação avançada (Slicing) para separar dados por cidades (Moscow, Kaliningrad, etc.).
3.  **Visualização de Dados:** Criação de gráficos de séries temporais utilizando `Matplotlib` para identificar padrões visuais.
4.  **Limpeza de Dados:** Identificação e tratamento de dados faltantes (`NaNs`) utilizando interpolação pela média.
5.  **Matemática Aplicada:**
    * Comparação de arrays (`allclose`).
    * Cálculo de coeficientes angulares.
    * Implementação manual de **Regressão Linear** para traçar linhas de tendência, calculando a norma (distância) entre a reta prevista e os dados reais.

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **NumPy:** Para computação científica, vetores e operações matriciais.
* **Matplotlib:** Para plotagem de gráficos 2D.

## 📊 Exemplo de Análise

Um dos pontos altos do projeto foi o cálculo da reta de ajuste (Regressão Linear) para entender a tendência de aumento de preços em Moscou:

```python
# Exemplo do cálculo do coeficiente angular realizado no projeto
Y = Moscow
X = datas
n = np.size(Moscow)

# Cálculo do coeficiente 'a' da reta y = ax + b
a = (n*np.sum(X*Y) - np.sum(X)*np.sum(Y))/(n*np.sum(X**2)-np.sum(X)**2)

📂 Como executar este projeto
Clone este repositório:

Bash

git clone [https://github.com/gabrielramos1403/seu-repositorio-aqui.git](https://github.com/gabrielramos1403/seu-repositorio-aqui.git)
Instale as dependências:

Bash

pip install numpy matplotlib
Execute o Jupyter Notebook:

Bash

jupyter notebook Curso_Numpy_Alura_bil.ipynb



📈 Dataset
Os dados utilizados referem-se aos preços de maçãs em regiões da Rússia, disponibilizados originalmente no repositório da Alura. O arquivo contém séries temporais separadas por cidades ao longo de vários anos.

🤝 Autor
Gabriel

Github: @gabrielramos1403

LinkedIn: https://www.linkedin.com/in/gabriel-ramos-941766355
