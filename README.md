# Recomendação de produtos por imagem

Este projeto implementa a biblioteca Annoy para coletar caracteristicas semelhantes dos produtos com 
base em uma imagem escolhida e utilizando o modelo pré-treinado do MobileNet do TensorFlow como base
para encontrar imagens com as caracteristicas semelhantes.


## Tecnologias Usadas

- Python 3.11
- TensorFlow: para carregar o modelo pré-treinado e extrair características das imagens.
- Annoy: para construir e pesquisar o índice de similaridade de imagens.
- Pillow: para o processamento e pré-processamento de imagens.
- NumPy: para operações de array e manipulação de dados.


## Requisitos

```bash
pip install tensorflow annoy numpy pillow
```
