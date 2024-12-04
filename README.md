# Classificação de Gênero com redes convolucionais (CNN)

## Objetivo do Projeto

Este projeto do Programa de Residência em software RESTIC36 tem como objetivo classificar imagens do dataset CUHK Face Sketch Database (CUFS) de acordo com o gênero (masculino ou feminino) utilizando redes neurais convolucionais (Convolutional Neural Networks - CNNs). O problema consiste em treinar e avaliar um modelo de aprendizado profundo projetado do zero para extração de características e classificação das imagens. 

Para isso etapas e métodos aplicados incluem desde o pré-processamento dos dados,, com ajustes de resolução, normalização e data augmentation, até a avaliação do modelo com métricas como F1-score, curva ROC e AUC-ROC.inluindo o pré-processamento dos dados

Os insights sobre o desempenho em um conjunto de dados limitado destaca os desafios de classificação e oportunidades de melhoria para abordagens futuras.


## Instruções para Execução do Código
### Requisitos de Software
- Python 3.8 ou superior

Bibliotecas necessárias instaladas via pip:
- tensorflow
- keras
- numpy
- matplotlib
- scikit-learn

### Passos para Execução
1. Clone o repositório do projeto: git clone https://github.com/brendabo1/CNN-classification-CUFS.git

2. Instale as dependências

3. Execute o arquivo cnn_face_sketch.ipynb

## Principais Conclusões e Considerações
O modelo desenvolvido alcançou um F1-score de 0.6824, o que indica um bom desempenho na tarefa de classificação de imagens do dataset CUFS. Esse valor reflete um equilíbrio razoável entre as taxas de precisão e recall, mas também sugere limitações na capacidade do modelo em lidar com casos mais complexos. Durante a análise, foi identificado que o modelo teve dificuldades em classificar imagens com características desafiadoras, como iluminação inadequada e características faciais menos pronunciadas. Esses fatores evidenciam a necessidade de aprimoramentos tanto nos dados quanto na arquitetura do modelo.

Entre as principais limitações do projeto, destaca-se o tamanho reduzido do dataset, que restringiu a capacidade de generalização do modelo. Além disso, o desbalanceamento nas classes de imagens masculinas e femininas pode ter influenciado os resultados, dificultando o aprendizado uniforme do modelo. Embora as técnicas de regularização e data augmentation tenham contribuído para mitigar parcialmente esses problemas, elas não foram suficientes para superar as limitações impostas pela qualidade e quantidade dos dados disponíveis.

Apesar das limitações, o projeto ofereceu aprendizados importantes sobre o design e treinamento de redes convolucionais. Ele também evidenciou os desafios de trabalhar com datasets pequenos e realçou a importância de estratégias de regularização e pré-processamento de dados. Trabalhos futuros podem explorar soluções mais avançadas para superar esses desafios e alcançar resultados mais expressivos.


