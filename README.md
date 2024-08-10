# Predicao-de-reinternacoes-hospitalares
**Descrição do Projeto**
Este projeto tem como objetivo prever reinternações hospitalares de pacientes utilizando técnicas de aprendizado de máquina. A reinternação hospitalar é um problema significativo no setor de saúde, resultando em altos custos e impactando negativamente a qualidade de vida dos pacientes. Ao prever quais pacientes têm maior probabilidade de serem reinternados, os hospitais podem implementar intervenções para reduzir essas ocorrências.

**Objetivos**
Explorar e entender os dados disponíveis: Compreender as características e padrões presentes nos dados.
Construir e comparar modelos preditivos: Avaliar diferentes algoritmos de aprendizado de máquina para identificar o mais eficaz na predição de reinternações.
Avaliar a performance dos modelos: Utilizar métricas como acurácia, ROC-AUC, e matriz de confusão para avaliar os modelos.
Propor intervenções: Basear-se nos resultados do modelo para sugerir ações que possam reduzir as reinternações.

**Tecnologias Utilizadas**
Python 3
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Imbalanced-learn (para tratamento de desbalanceamento dos dados)

**Estrutura do Projeto**
Introdução: Discussão sobre o problema das reinternações hospitalares e os objetivos do projeto.
Importação de Bibliotecas: Listagem e importação das bibliotecas necessárias.
Análise Exploratória de Dados (EDA): Exploração e visualização dos dados para identificar padrões e relações.
Pré-processamento de Dados: Limpeza e preparação dos dados, incluindo tratamento de desbalanceamento com SMOTE.
Treinamento e Avaliação de Modelos: Construção e avaliação de três modelos preditivos - Regressão Logística, Random Forest e Support Vector Machine (SVM).
Avaliação Final: Análise da matriz de confusão e da curva ROC para o melhor modelo.
Conclusão: Resumo dos resultados obtidos e considerações finais sobre o projeto.

**Resultados**
Melhor Modelo: O modelo de Random Forest apresentou o melhor desempenho com uma acurácia e ROC-AUC que indicam uma boa capacidade preditiva.
Métricas:
Regressão Logística: Acurácia: X.XX, ROC-AUC: X.XX
Random Forest: Acurácia: X.XX, ROC-AUC: X.XX
SVM: Acurácia: X.XX, ROC-AUC: X.XX
Os resultados indicam que a Random Forest é o modelo mais eficaz, com uma boa capacidade de prever quais pacientes têm maior probabilidade de serem reinternados.
