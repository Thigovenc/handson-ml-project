# 🚀 Projeto de Regressão: Previsão de Preços de Imóveis 🏠

Este repositório documenta minha jornada de aprendizado ao implementar o projeto ponta-a-ponta do Capítulo 2 do livro **"Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow"** (2ª Edição) de Aurélien Géron.

O objetivo é construir um modelo de regressão capaz de prever o valor mediano de imóveis em distritos da Califórnia, utilizando dados do censo de 1990.

---

## 🎯 Objetivo Principal

O foco deste projeto não é apenas criar um modelo, mas sim praticar e solidificar o **processo completo de um projeto de Machine Learning** no mundo real.

Isso inclui desde a obtenção dos dados até a avaliação final do sistema.

## 📈 O Pipeline de ML

Seguindo a metodologia do livro, o projeto é dividido nas seguintes etapas:

1.  **📥 Aquisição dos Dados:**
    * Criação de scripts para baixar e carregar o dataset (`housing.csv`).

2.  **🔭 Análise Exploratória (EDA):**
    * Investigar as *features* (atributos) dos dados.
    * Criar visualizações gráficas (histogramas, *scatter plots*) para encontrar padrões e correlações.
    * Analisar a correlação entre os atributos e o valor mediano (`median_house_value`).

3.  **🧹 Preparação e Pré-processamento:**
    * Limpeza de dados: Tratar valores ausentes (ex: `total_bedrooms`).
    * Engenharia de *features*: Criar novos atributos relevantes (ex: `rooms_per_household`).
    * Construção de *Pipelines* do Scikit-Learn para automatizar a transformação de dados (tratamento de texto, normalização, etc.).

4.  **🤖 Treinamento e Seleção de Modelos:**
    * Treinamento de múltiplos modelos de regressão (Regressão Linear, Árvore de Decisão, Random Forest, etc.).
    * Avaliação inicial dos modelos usando Validação Cruzada (*Cross-Validation*).

5.  **⚙️ Otimização e Avaliação Fina:**
    * Ajuste fino (*fine-tuning*) dos hiperparâmetros dos melhores modelos usando `GridSearchCV`.
    * Avaliação final do sistema no conjunto de teste para estimar o desempenho em dados nunca vistos.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python 3.x**
* **Pandas:** Para manipulação e análise eficiente dos dados.
* **Scikit-Learn (sklearn):** A biblioteca central para o pipeline de ML, pré-processamento, modelagem e avaliação.
* **NumPy:** Para operações numéricas.
* **Matplotlib & Seaborn:** Para a visualização de dados e *insights*.
* **Jupyter Notebook:** (Se você estiver usando) Para desenvolvimento iterativo e documentação.

## 📖 Fonte

Este projeto é um exercício de estudo baseado no Capítulo 2 do livro "Hands-On Machine Learning" e utiliza o [dataset clássico da Califórnia](https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.tgz) disponibilizado pelo autor.
