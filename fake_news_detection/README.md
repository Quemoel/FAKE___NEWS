# Detecção de Fake News

Este é um projeto de detecção de fake news utilizando aprendizado de máquina. O objetivo é classificar notícias em reais ou falsas com base no texto do artigo.

## Requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

- pandas
- matplotlib
- seaborn
- nltk
- scikit-learn
- joblib
- Flask

Você pode instalá-las usando o gerenciador de pacotes `pip`. Por exemplo:



## Estrutura de arquivos

A estrutura de arquivos do projeto é organizada da seguinte maneira:

fake_news_detection/
├── data/
│ └── news.csv
├── models/
│ └── fake_news_model.pkl
├── src/
│ └── main.py
├── utils/
│ └── preprocess.py
└── templates/
└── index.html
pcodigo.ipynb


- A pasta `data` contém o arquivo CSV com os dados das notícias.
- A pasta `models` armazena o modelo treinado em formato pickle (`.pkl`).
- A pasta `src` contém o arquivo principal do projeto, `main.py`.
- A pasta `utils` contém o arquivo `preprocess.py` que contém funções de pré-processamento de texto.
- A pasta `templates` contém o arquivo `index.html` para a interface web.

## Uso

1. Certifique-se de ter instalado todas as bibliotecas listadas nos requisitos.

2. Baixe o conjunto de dados de notícias e salve-o como `news.csv` na pasta `data`.

3. Execute o arquivo `main.py` para treinar o modelo, realizar a classificação e iniciar o aplicativo Flask:

python src/main.py


4. Abra o navegador e acesse `http://localhost:5000` para usar a interface web de classificação.

5. Insira o texto da notícia e clique no botão "Classificar" para obter a previsão.

6. Você também pode avaliar o aplicativo fornecendo uma pontuação de 1 a 5 estrelas e um comentário.

## Contribuição

Sinta-se à vontade para contribuir para este projeto, abrindo issues e pull requests.
