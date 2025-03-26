# Classificador de Dígitos MNIST

Este é um projeto de classificação de dígitos utilizando a base de dados **MNIST** com redes neurais desenvolvidas em **PyTorch**.

## Descrição

O objetivo deste projeto é construir e treinar uma rede neural simples para classificar imagens de dígitos manuscritos (0-9) presentes no dataset **MNIST**. A rede é composta por duas camadas totalmente conectadas e utiliza a função de ativação **ReLU** para a camada oculta e **Softmax** para a camada de saída. O modelo foi treinado utilizando o otimizador **Adam** e a função de custo **Cross Entropy Loss**.

## Tecnologias Utilizadas

- **PyTorch**: Framework para construção e treinamento de redes neurais.
- **Torchvision**: Biblioteca para carregar datasets de visão computacional, como o MNIST.
- **Matplotlib**: Usada para visualizar as imagens do dataset.
  
## Resultado Final
Acurácia no conjunto de teste: 96.98%
