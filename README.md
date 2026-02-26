# Day/Night Classification Model

Modelo CoreML treinado para classificar imagens em três categorias: **dia**, **noite** e **crepúsculo**.

## Modelo
- Arquivo: `dayNightClassification 1.mlmodel`
- Framework: Apple Create ML + CoreML
- Feature Extractor: Image Feature Print V2
- Acurácia: 99% treino / 97% validação / 100% teste

## Dataset
Dataset original: [Day-night Computer Vision Model](https://universe.roboflow.com/emma-feoktistova/day-night-computer-vision-model) por Emma Feoktistova, disponível no Roboflow Universe.
- 3.100 imagens
- 3 classes: day, night, twilight
- Licença: consultar README.dataset.txt

## Estrutura
```
train/   → imagens de treino
valid/   → imagens de validação  
test/    → imagens de teste
```

## Como usar no Xcode
Arraste o `.mlmodel` para o projeto → marque o target → use via `VNCoreMLModel`.
