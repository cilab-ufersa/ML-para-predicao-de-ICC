## Aprendizado de Máquina Para a Predição da Isuficiência Cardíaca Crônica

Esse projeto tem como objetivo utilizar modelos de machine learning para predizer a insuficiência cardíaca crônica em pacientes que sofreram com infarto do miocárdio. Para isso foi utilizado o dataset UC Irvine Machine Learning Repository, que contem dados clinicos sobre pacientes que sofreram com IM e suas possíveis complicações.

O projeto foi realizado nos seguintes passos:

1 - Pré-processamento de dados;
2 - Treinamento dos modelos;
3 - Análise dos resultados obtidos nos treinamentos;
4 - Utilização de técnicas de balanceamento de dados;

No pré-processamento de dados foi feito a limpeza e seleção de features. O treinamento dos modelos foi realizado usando a linguagem de programação Python, no Jupyter Notebook, e as bibliotecas lightgbm e scikit learn nos modelos de machine learning Decision Tree, Random Forest e LightGBM. A análise dos resultados desses treinamentos foi feita sobre os dados das métricas disponibilizadas pela função classification report da biblioteca sklearn.metrics e as técnicas Cross Validation, Matriz de Confusão e Curva ROC. Foi necessário a utilização das técnicas de balanceamento de dados Up-Sampling e Down-Sampling pois a análise dos resultados demonstrou um desbalanceamento entre as amostras da classe 'ZSN'.

Outras bibliotecas utilizadas foram numpy, pandas e matplotlib.
