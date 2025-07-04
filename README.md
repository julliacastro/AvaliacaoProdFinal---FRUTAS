🥭 Avaliação ProdFinal — FRUTAS

Este projeto utiliza o modelo YOLO (You Only Look Once) para detecção e classificação de frutas em imagens, como parte de uma avaliação final de produção.

📂 Estrutura do Projeto

TrabalhoYOLO2 - Frutas.ipynb: Notebook com todo o código de treinamento, inferência e avaliação do modelo.

args.yaml: Configurações de parâmetros do modelo.

results.csv: Resultados quantitativos (ex: precisão, recall, F1-score).

Pastas de imagens, anotações.

🚀 Tecnologias Utilizadas

Python

YOLOv5 / YOLOv8 (dependendo da versão usada)

OpenCV

Pandas

Numpy

Matplotlib

PyTorch (para treinamento)

📊 Métricas

As principais métricas utilizadas para avaliação foram:

Precisão (Precision)

Revocação (Recall)

F1-Score

Essas métricas foram registradas no arquivo results.csv.

🔧 Como Executar

Clone o repositório:

git clone https://github.com/julliacastro/AvaliacaoProdFinal---FRUTAS.git

Instale as dependências (exemplo com requirements.txt):

pip install -r requirements.txt

Execute o notebook:

Abra TrabalhoYOLO2 - Frutas.ipynb em um ambiente como Jupyter Notebook ou Google Colab.
