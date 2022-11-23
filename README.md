# Early Prediction of diabetes
&nbsp;
> Análise Exploratório de Dados e Modelo preditivo para diagnóstico precoce de diabetes por meio de questionários de sintomas usando modelos de machine learning e linguagem python.

&nbsp;

Diabetes é uma doenças muito comum em todo o mundo. Seu diagnóstico precoce pode reduzir sua gravidade assim como fatores de risco. O diagnóstico precoce pode ocorrer pela análise sintomática o quanto antes possível. Isso também contribui para ampliar a conscientização dos primeiros sinais de diabetes.
 
Algoritmos de classificação de aprendizagem de máquina, tais como, **Regressão Logística** (LR - Logistic Regression), **K Vizinhos Mais Próximos** (KNN - K-Nearest Neighbours), **Árvore de Decisão** (DT - Decision Tree), **Floresta Aleatória** (RF - Random Forest) e **Aumento do Gradiente** (Gradient Boosting - GB) foram treinados e avaliados para detecção de diabetes. Além disso, para ajuste de himeparâmetros foi aplicada a otimização de hiperparâmetros pelo grid search.

&nbsp;

### **Objetivos principais:**
---
- Realizar o teste de hipótese sendo a hipótese nula:

*H0: É factível o diagnótico precose de diabetes por meio de qustionários sobre seus sintomas comuns, considerando acurácia superior a 80%.*

- Obter insights explorando as relações entre as variáveis independentes e a variável dependente.

&nbsp;

### **Descrição do conjunto de dados**
---
Este conjunto de dados contém dados de sintomas de recém-diabéticos e não diabéticos do nordeste do sul da Ásia (Bangladesh). Ele inclui 16 variáveis independentes e a variável dependente 'Classe'.

**Fonte:** Repositório de aprendizagem de máquina da Universidade da Califónia, Irvine

**Disponível em:** https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset

&nbsp;

### **Dependências**
---
```sh
import pandas as pd
import numpy as np
import sklearn 
import matplotlib.pyplot as plt
import seaborn as sns
```

&nbsp;

### **Principais resultados obtidos em relação às métricas de performance dos modelos**
---
Métricas de Performance | Logistic Regression | KNN | Decision Tree | Random Forest | Gradient Boosting
---|:---:|:---:|:---:|:---:|:---:
Accuracy	| 0.923 |	0.949 |	0.949 |	0.981 |	0.974
Precision	| 0.957 |	1.000 |	0.989 |	0.979 |	0.989
Recall	    | 0.917 |	0.917 |	0.927 |	0.990 |	0.969
F-1 Score	| 0.936 |	0.957 |	0.957 |	0.984 |	0.979





