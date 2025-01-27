Transfer Learning utilizando Phyton para classificação entre cavalo e humanos;
Rede utilizada: ResNet50 - imagenet
Dataset: tensorflow
Pré-processamento dos dados: As imagens foram redimensionadas para 224x224 pixels e normalizadas para atender aos requisitos do modelo ResNet50.
Criação do modelo: Utilizado o ResNet50 como base, adicionando camadas densas ao topo para ajustar o modelo à tarefa específica de classificação binária.
Treinamento e fine-tuning: Inicialmente, congelado todas as camadas do modelo base, treinando apenas as camadas adicionadas. Posteriormente, realizamos um ajuste fino descongelando as últimas camadas do modelo base.
Validação e teste: O modelo foi avaliado em um conjunto de validação, alcançando boa precisão na tarefa de classificação.
