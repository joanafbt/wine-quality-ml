# 🍷 Predição da Qualidade do Vinho com Machine Learning

## Objetivo
Desenvolver e comparar modelos de machine learning para prever a qualidade
de vinhos portugueses (tintos e brancos) com base nas suas características
físico-químicas, com o objetivo de apoiar decisões na produção e controlo
de qualidade.

## Ferramentas e tecnologias
- Weka (modelação e avaliação de modelos)
- Dataset: UCI Machine Learning Repository — Wine Quality Dataset
- ~5300 observações | variáveis: álcool, acidez, pH, sulfatos, entre outras

## Modelos comparados
| Modelo              | Notas                              |
|---------------------|------------------------------------|
| Regressão Linear    | Baseline do estudo                 |
| Random Forest       | Bom desempenho geral               |
| Gradient Boosting   | Melhor modelo (resultado final)    |

## Resultados
- **Melhor modelo:** Gradient Boosting
- O modelo explica ~35% da variabilidade da qualidade do vinho
- Random Forest apresentou desempenho competitivo
- Regressão Linear serviu como baseline comparativo

## Principais insights
- O teor alcoólico é o fator com maior impacto na qualidade (~26%)
- A acidez volátil tem impacto negativo na qualidade percebida
- A qualidade do vinho é multifatorial — não depende de uma única variável
- Existem diferenças relevantes nos padrões entre vinhos tintos e brancos

## Aplicação prática
- Apoio ao controlo de qualidade na produção vinícola
- Identificação das variáveis críticas no processo de fermentação
- Base para sistemas de recomendação e decisão baseados em dados

## Publicação
Este trabalho foi apresentado numa conferência científica e resultou
numa publicação académica.

---
*Dataset: [UCI Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)*
