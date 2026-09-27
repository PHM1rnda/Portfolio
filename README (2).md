# Regressão Linear, Ridge e Lasso

Estudo comparativo de modelos lineares e regularização L1/L2 em um problema de regressão.

## Destaques
- `PolynomialFeatures` para expansão das características;
- Regressão Linear;
- Ridge (L2) com diferentes valores de `alpha`;
- Lasso (L1) com diferentes valores de `alpha`;
- comparação visual dos coeficientes;
- observação da seleção de atributos produzida pelo Lasso.

## Tecnologias
Python · NumPy · Matplotlib · Scikit-learn

## Dataset
O projeto mantém o tema do Boston Housing Dataset. A versão atual usa `fetch_openml` em vez do antigo `load_boston`, que foi removido do scikit-learn.

## Como executar
```bash
pip install -r requirements.txt
jupyter notebook Regressao_Linear_Ridge_Lasso_portfolio.ipynb
```
