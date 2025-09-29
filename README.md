# Transfer Learning (PyTorch): Classificação de Imagens (Cães vs. Gatos)

-----------------------------------------------------------------------------------------------------------------------

Sobre o Projeto
Este projeto demonstra a aplicação de **Transfer Learning** para classificar imagens em duas categorias (cães e gatos). Utiliza uma rede neural pré-treinada (ResNet18) e a ajusta para um novo conjunto de dados com eficiência e alta performance.

O objetivo é provar a capacidade de trabalhar com **Modelos de Visão Computacional (CV)** e otimizar o tempo de treinamento, uma técnica crucial em Machine Learning.

-----------------------------------------------------------------------------------------------------------------------

##  Tecnologias e Métodos
* **Framework:** PyTorch
* **Modelo Base:** ResNet18 (pré-treinada no ImageNet)
* **Método:** **Transfer Learning (Fine-Tuning)** 
* **Bibliotecas de Processamento:** `torchvision`, `torch.nn`, `torch.optim`

-----------------------------------------------------------------------------------------------------------------------

## Entregas Técnicas e Resultados
* **Aceleração de Treinamento:** Uso do *Transfer Learning* para atingir resultados satisfatórios com um número menor de épocas.
* **Modificação de Arquitetura:** Substituição da camada **Fully Connected** da ResNet18 para adaptar o modelo a 2 classes.
* **Pré-Processamento de Imagens:** Aplicação correta de transformações (`Resize`, `ToTensor`, `Normalize`) exigidas pelo modelo base.
* **Validação:** O código inclui a estrutura para testes futuros e predição de novas imagens (demonstrada na captura de tela anexa).

-----------------------------------------------------------------------------------------------------------------------

# Codigo disponivel no colab, usando o link abaixo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gcCoEnJQhQCS4n9YAPwr--Gqx1F8bOh4?usp=sharing)

