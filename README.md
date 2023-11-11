# Breast Cancer Detection AI System

De acordo com a explicação no artigo, o seguinte código apresenta os processos do sistema de detecção de câncer de mama. 

Usando técnicas de pré-processamento, uso de Transfer Learning, além de uma arquitetura de Rede Neural Residual (ResNet50), o modelo de previsão detecta câncer de mama com uma acurácia de 73,29% durante a validação, e 52% durante os testes.

O modelo utilizado pode ser encontrado no arquivo TCC2_MODELS.ipynb, um Notebook Jupiter que integra códigos, explicações e imagens, juntamente com processos como importação das imagens, pré-processamento, aplicação do método de Transfer Learning, declaração do modelo e treinamento, além de métricas e previsões.



## Base de dados

Em função da base de imagens ser muito grande, os diretórios se encontram no [Google Drive](https://drive.google.com/drive/folders/1dLuh5ZCn1lfqwx5gEmfldaShSq9TtLnf?usp=drive_link).

A base foi dividida em 6 grupos:

* Imagens para **treinamento** de pacientes **SEM** câncer

* Imagens para **treinamento** de pacientes **COM** câncer

* Imagens para **validação** de pacientes **SEM** câncer

* Imagens para **validação** de pacientes **COM** câncer

* Imagens para **teste** de pacientes **SEM** câncer

* Imagens para **teste** de pacientes **COM** câncer