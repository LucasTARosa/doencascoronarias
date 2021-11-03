# :hammer_and_wrench: Machine Learning aplicada para detecção de doenças coronárias :heart: :hospital: :syringe: 

Seja muito bem-vindo a este projeto de Data Science :sparkler: 

Este projeto foi desenvolvido como parte da formação no curso de Data Expert, fornecido pela Dinâmica Group (DNC). 

O banco de dados utilizado é público e se encontra disponível no Kaggle (https://www.kaggle.com/ronitf/heart-disease-uci)



## Introdução

Este dataset é composto por 13 features sobre 303 pacientes diferentes e com um target, que representa a existência ou não de doenças coronárias (doenças do coração). 

Este tipo de modelo tem uma grande importância, já que pode ajudar a detectar uma possível doença cardíaca com antecedência, aumentando a chance de sobrevivência do paciente e da qualidade de vida.



## Análise exploratória

Foi realizada a análise exploratória dos dados, obtendo insights sobre características que aumentam a propensão ao desenvolvimento de doenças coronárias. Além disto, foi verificada a existência de dados nulos, outliers e variáveis categóricas.



## Modelo e Hiperparametrização

Os melhores modelos foram escolhidos com base no F1-score, com o modelo de regressão logística apresentando o maior F1-score (88.48%) para a condição default, seguido pelo modelo de Random Forest (85.18%).

Após o processo de tuning, o modelo de regressão logística teve um ganho pequeno, chegando a 88.51%. Já o modelo de Random Forest teve um ganho mais significativo, alcançando os mesmos 88.51% do modelo de regressão. 