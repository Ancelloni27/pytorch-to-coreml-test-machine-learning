{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Day/Night Classification Model\
\
Modelo CoreML treinado para classificar imagens em tr\'eas categorias: **dia**, **noite** e **crep\'fasculo**.\
\
## Modelo\
- Arquivo: `dayNightClassification 1.mlmodel`\
- Framework: Apple Create ML + CoreML\
- Feature Extractor: Image Feature Print V2\
- Acur\'e1cia: 99% treino / 97% valida\'e7\'e3o / 100% teste\
\
## Dataset\
Dataset original: [Day-night Computer Vision Model](https://universe.roboflow.com/emma-feoktistova/day-night-computer-vision-model) por Emma Feoktistova, dispon\'edvel no Roboflow Universe.\
- 3.100 imagens\
- 3 classes: day, night, twilight\
- Licen\'e7a: consultar README.dataset.txt\
\
## Estrutura\
```\
train/   \uc0\u8594  imagens de treino\
valid/   \uc0\u8594  imagens de valida\'e7\'e3o  \
test/    \uc0\u8594  imagens de teste\
```\
\
## Como usar no Xcode\
Arraste o `.mlmodel` para o projeto \uc0\u8594  marque o target \u8594  use via `VNCoreMLModel`.}