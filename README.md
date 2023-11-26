# o modelo main tem 40% trein, 35% valid, 25% test
# o google drive tem 2 bases 
## a de 25porcento é a que eu uso no modelo main. a 9_4porcento é a que usava antes - só que com q quantidade certa no test (9,4%)

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


## Executando o código

Para executar o código localmente, é necessário possuir a versão 3.10 do Python e configurar o sistema para reconhecê-la corretamente.

Além disso, é necessário instalar os seguintes pacotes, utilizando o comando `pip install (pacotes)`:

- numpy 
- matplotlib
- opencv-python 
- tensorflow 
- pillow 
- pandas 
- scipy 
- keras 
- scikit-learn
- seaborn


Certifique-se de que todos os pacotes estão instalados antes de prosseguir.

Com os pacotes instalados, descompacte o arquivo `DATASETS.zip` na raiz do programa. A estrutura de diretórios deve seguir este padrão:



- **DATASETS/**: Contém os conjuntos de dados divididos em treinamento, teste e validação, cada um com subdiretórios para amostras com câncer e sem câncer.
- **logs/**: Possivelmente um diretório para armazenar logs relacionados ao seu projeto.
- **.gitignore**: Um arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo sistema de controle de versão Git.
- **README.md**: Um arquivo markdown que geralmente contém informações sobre o projeto, instruções de uso e qualquer outra documentação relevante.
- **TCC2_MODELS.upynb**: Um arquivo Jupyter Notebook para o seu trabalho de conclusão de curso (TCC) relacionado aos modelos.



/
|-- DATASETS/
    |-- TESTING
        |-- WITH CANCER
            |-- ...
        |-- WITHOUT CANCER
            |-- ...
    |-- TRAINING
        |-- WITH CANCER
            |-- ...
        |-- WITHOUT CANCER
            |-- ...
    |-- VALIDATION
        |-- WITH CANCER
            |-- ...
        |-- WITHOUT CANCER
            |-- ...
|-- logs/     
|-- .gitignore
|-- README.md
|-- TCC2_MODELS.upynb




Certifique-se de organizar os dados dessa maneira para garantir o correto funcionamento do código.
