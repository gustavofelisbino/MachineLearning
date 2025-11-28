# 🛍️ Recomendação Inteligente de Produtos (E-commerce)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Jupyter](https://img.shields.io/badge/Environment-Jupyter-F37626)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 📄 Sobre o Projeto

Este projeto é um **Sistema de Recomendação de Produtos** desenvolvido como Trabalho Final acadêmico de Machine Learning. 

O objetivo é prever a probabilidade de compra de um usuário com base em dados históricos, utilizando e comparando duas abordagens clássicas:
1.  **KNN (K-Nearest Neighbors):** Filtragem baseada em similaridade/distância.
2.  **Random Forest:** Classificação baseada em ensemble de árvores de decisão.

O projeto utiliza o dataset real da **Olist** (E-commerce brasileiro), focado em resolver o problema da "sobrecarga de informação" e aumentar a conversão de vendas através de sugestões personalizadas.

---

## 📊 Resultados Alcançados

O modelo **Random Forest** apresentou desempenho superior ao KNN, lidando melhor com a mistura de dados numéricos (preço) e categóricos (categorias).

| Modelo | Acurácia | Precision | Recall |
| :--- | :---: | :---: | :---: |
| **KNN** | 64% | 63% | 69% |
| **Random Forest (Campeão)** | **66%** | **65%** | **73%** |

> **Insight:** O Random Forest obteve um **Recall de 73%**, o que significa que ele é eficaz em identificar a maioria das oportunidades reais de venda, minimizando a perda de receita.

---

## 📂 Estrutura do Repositório

* `analise_exploratoria.ipynb`: Notebook contendo a **EDA (Análise Exploratória de Dados)**. Gera gráficos de Curva ABC, distribuição de preços e análise de avaliações.
* `modelagem.ipynb`: Notebook com o pipeline completo de **Machine Learning** (Pré-processamento, Treinamento do KNN e Random Forest, e Avaliação de Métricas).
* `requirements.txt`: Lista das bibliotecas necessárias para rodar o projeto.

---

## 🚀 Como Executar o Projeto

Para rodar este projeto na sua máquina local, siga os passos abaixo:

### 1. Pré-requisitos
* Python instalado.
* Git instalado.

### 2. Clonar o Repositório

``` bash
git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
cd SEU-REPOSITORIO
```

### 3. Instalar Dependências
Recomenda-se usar um ambiente virtual (venv).
``` bash
pip install -r requirements.txt
```
### 4. Baixar o Dataset
Os dados não estão incluídos no repositório devido ao tamanho.

Acesse o Brazilian E-Commerce Public Dataset by Olist no Kaggle.

Baixe o arquivo .zip e extraia.

Coloque os arquivos .csv (ex: olist_order_items_dataset.csv, olist_products_dataset.csv, etc.) na raiz da pasta do projeto.

### 5. Executar os Notebooks
Abra o Jupyter Notebook ou Jupyter Lab:

``` bash
jupyter notebook
Execute os arquivos na seguinte ordem:

analise_exploratoria.ipynb (Para visualizar os gráficos e entender os dados).

modelagem.ipynb (Para treinar os modelos e ver as previsões).
```
### 🛠️ Tecnologias Utilizadas
- Linguagem: Python

- Manipulação de Dados: Pandas, Numpy

- Visualização: Matplotlib, Seaborn

- Machine Learning: Scikit-learn (Sklearn)

## 📝 Autor

Desenvolvido por Gustavo, Lucas e Tiago.

Projeto apresentado para a disciplina de Machine Learning do curso de Engenharia de Software.
