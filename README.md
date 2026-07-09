# 🍷 Wine Quality Classification

## Descrição
Projeto de Machine Learning desenvolvido como Tech Challenge da Fase 2 do programa POSTECH DTAT.

O objetivo é classificar a qualidade de vinhos tintos como **Alta Qualidade** (nota ≥ 7) ou **Baixa/Média Qualidade** (nota < 7) com base em suas características físico-químicas.

## Dataset
- **Fonte:** [Wine Quality Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)
- **Amostras:** 1.143 vinhos
- **Variáveis:** 11 características físico-químicas + variável alvo

## Metodologia
1. Análise Exploratória de Dados (EDA)
2. Pré-processamento e normalização
3. Treinamento de modelos de classificação
4. Avaliação e comparação dos modelos

## Modelos Utilizados
| Modelo | Accuracy | ROC-AUC |
|--------|----------|---------|
| Regressão Logística | 79.9% | 0.850 |
| Random Forest | 91.3% | 0.901 |

## Principais Resultados
- **Melhor modelo:** Random Forest (ROC-AUC 0.901)
- **Variável mais importante:** Teor alcoólico (alcohol)
- **Segunda mais importante:** Sulfatos (sulphates)
- **Variável mais prejudicial à qualidade:** Acidez volátil (volatile acidity)

## Estrutura do Repositório
wine-quality-classification/
├── data/          # Base de dados utilizada
├── notebooks/     # Notebook com análise e modelagem
├── src/           # Scripts auxiliares
├── results/       # Gráficos e métricas dos modelos
├── requirements.txt
└── README.md
## Tecnologias
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
