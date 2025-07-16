Pix2Pix GAN - Image-to-Image Translation

English

📌 Project Description

This project is a full implementation of the Pix2Pix GAN, built from scratch using PyTorch. Pix2Pix is a type of Conditional GAN designed for image-to-image translation tasks using paired image datasets. Example applications include converting sketches to photos, satellite images to maps, and more.

🚀 Features

Full Pix2Pix architecture implemented in a single, interactive notebook

Generator based on U-Net for high-quality image generation

Discriminator based on PatchGAN for local-level detail evaluation

Custom training loop with adversarial and L1 loss

Easily modifiable and visual step-by-step implementation for learning and experimentation

🛠️ Technologies Used

Python

PyTorch

NumPy

OpenCV

Jupyter Notebook

📁 Dataset

Supports paired image datasets, including:

CMP Facades

Satellite ↔ Map

Custom aligned image pairs

Each sample must consist of an input image (e.g., edge map) and its corresponding target image (e.g., photo).

🔧 Setup Instructions

Clone the repository:

git clone https://github.com/Viitor22/Pix2Pix.git

Navigate to the project directory:

cd Pix2Pix

Install required dependencies:

pip install -r requirements.txt

Launch the Jupyter Notebook:

jupyter notebook

Open Pix2Pix.ipynb and follow the instructions in the cells to train and test the model.

📊 Usage

Load your dataset under the data/ directory (following the required format)

Run training and generation steps inside the notebook

Visualize model outputs and loss curves inline

📌 Contributing

Feel free to fork this repository and contribute by adding new datasets, improving the architecture, or enhancing the notebook!

Português

📌 Descrição do Projeto

Este projeto é uma implementação completa da GAN Pix2Pix, feita dentro de um Jupyter Notebook, utilizando PyTorch do zero. O modelo Pix2Pix é uma GAN condicional voltada para tarefas de tradução imagem-para-imagem com conjuntos de dados pareados. Exemplos incluem converter esboços em fotos, imagens de satélite em mapas, entre outros.

🚀 Funcionalidades

Arquitetura completa da Pix2Pix em um único notebook interativo

Gerador baseado em U-Net para geração de imagens detalhadas

Discriminador baseado em PatchGAN para avaliação local da imagem

Loop de treinamento customizado com perdas adversarial e L1

Estrutura ideal para aprendizado, visualização e ajustes rápidos

🛠️ Tecnologias Utilizadas

Python

PyTorch

NumPy

OpenCV

Matplotlib & Seaborn

Jupyter Notebook

📁 Conjunto de Dados

Compatível com datasets pareados, como:

CMP Facades

Mapas ↔ Satélite

Conjuntos personalizados com pares alinhados

Cada par deve conter uma imagem de entrada (ex: mapa de bordas) e sua imagem alvo (ex: foto).

🔧 Instruções de Configuração

Clone este repositório:

git clone https://github.com/Viitor22/Pix2Pix.git

Acesse a pasta do projeto:

cd Pix2Pix

Instale as dependências:

pip install -r requirements.txt

Inicie o Jupyter Notebook:

jupyter notebook

Abra o arquivo Pix2Pix.ipynb e siga as instruções das células para treinar e testar o modelo.

📊 Uso

Coloque seu dataset na pasta data/ no formato correto

Execute as células do notebook para treinar e gerar imagens

Visualize os resultados e gráficos diretamente no notebook

📌 Contribuição

Sinta-se à vontade para fazer um fork do repositório e contribuir com melhorias, novos datasets ou otimizações!

📩 For any inquiries, contact: ianvib200@gmail.com

