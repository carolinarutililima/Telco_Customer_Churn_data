# 📊 Predição de Churn — Telco Customer Dataset

Este projeto utiliza o dataset **Telco Customer Churn** para prever a probabilidade de cancelamento de clientes (churn) em uma empresa de telecomunicações.  
O pipeline completo inclui **limpeza de dados, engenharia de features, treino de múltiplos modelos de classificação e análise de resultados**.

---

## 📂 Estrutura do Projeto

- `code.ipynb` → Notebook principal com todo o pipeline:
  1. **Carregamento e limpeza dos dados** (tratamento de valores ausentes e inconsistências).
  2. **Engenharia de features** (one-hot encoding, padronização de variáveis).
  3. **Divisão em treino e teste** (80/20 com estratificação).
  4. **Treinamento de modelos de classificação**:
     - Regressão Logística  
     - Random Forest  
     - Gradient Boosting  
     - Support Vector Machine (SVM)  
     - K-Nearest Neighbors (KNN)  
  5. **Avaliação de desempenho** (Acurácia, Precisão, Recall, F1-Score, AUC-ROC).
  6. **Visualizações** (curvas ROC e matrizes de confusão).
  7. **Análise de importância das features** (árvores de decisão, coeficientes, permutation importance e SHAP).
  8. **Insights de negócio** para retenção de clientes.

---

## ⚙️ Requisitos

O projeto foi desenvolvido em **Python 3.9+**.  
Pacotes necessários (instalar via `pip install -r requirements.txt` ou manualmente):

- pandas  
- numpy  
- scikit-learn  
- matplotlib  


---

## ▶️ Como Executar

1. Clone este repositório ou baixe os arquivos.  
2. Abra o notebook Jupyter:  
   ```bash
   jupyter notebook code.ipynb
