# Regras de Associação — Market Basket Analysis

Projeto de mineração de dados com Apriori para descobrir padrões de compra em transações.

## O que foi desenvolvido
- codificação de transações;
- geração de itemsets frequentes;
- regras de associação;
- análise de suporte, confiança e lift;
- filtragem das regras;
- análise da base Online Retail para França e Alemanha.

## Tecnologias
Python · Pandas · NumPy · Matplotlib · MLxtend

## Dataset
A análise utiliza a base Online Retail da UCI. O arquivo não está incluído neste repositório. Coloque `Online Retail.xlsx` em `data/online-retail/`.

## Como executar
```bash
pip install -r requirements.txt
jupyter notebook Regras_de_Associacao_Market_Basket_portfolio.ipynb
```

## Métricas
**Suporte** mede a frequência de uma combinação. **Confiança** mede a frequência do consequente dado o antecedente. **Lift** mede a associação relativa entre os itens; lift maior que 1 indica associação positiva segundo essa métrica e não deve ser interpretado como causalidade.
