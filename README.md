# 🧠 Classificação de Minas vs Rochas usando Sonar

Este projeto aplica **Análise Exploratória de Dados (EDA)**, **Redução de Dimensionalidade (PCA e LDA)** e **Modelagem de Machine Learning (K-Nearest Neighbors - KNN)** para classificar sinais de sonar como **minas** ou **rochas**.

O conjunto de dados utilizado foi o **Sonar Mines vs Rocks Dataset** disponível no **Repositório UCI Machine Learning**.

---

## 📈 Visão Geral do Projeto

- **Fonte de Dados**: UCI Machine Learning Repository - Sonar Dataset.
- **Objetivo**: Classificar retornos de sinais de sonar como **Mina (M)** ou **Rocha (R)**.
- **Técnicas Utilizadas**:
  - Inspeção e limpeza de dados (verificação de valores nulos, análise de distribuições)
  - Análise estatística (correlação de Pearson, variância)
  - Visualização de dados (Heatmaps, Boxplots, Pairplots)
  - Redução de dimensionalidade usando **PCA** e **LDA**
  - Construção de modelo com **K-Nearest Neighbors (KNN)**
  - **Otimização de hiperparâmetros** utilizando GridSearchCV (métricas de acurácia e F1-score)
  - Avaliação dos modelos (Matriz de Confusão, Relatórios de Classificação)

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- UCImlrepo

---

## 🏧 Estrutura do Projeto

```bash
👣 data/                # Carregamento do dataset (a partir da UCI)
👣 notebooks/           # Análise exploratória e modelagem (este notebook)
👣 README.md            # Descrição do projeto (você está aqui)
```

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Instale as bibliotecas necessárias:
```bash
pip install -r requirements.txt
```
*(Ou instale manualmente: pandas, numpy, seaborn, matplotlib, scikit-learn, ucimlrepo)*

3. Abra o notebook:
```bash
jupyter notebook Mina_Rocha.ipynb
```

---

## 📊 Resultados

- **Principais descobertas**:
  - Alguns atributos apresentam forte correlação com a classe alvo.
  - Técnicas de redução de dimensionalidade (PCA e LDA) mostraram boa separação visual das classes.
  - O algoritmo KNN obteve bons resultados após a otimização dos hiperparâmetros.

---

## 📚 Referências

- [UCI Machine Learning Repository - Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))




