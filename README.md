# Projeto Final - Modelos Preditivos Conexionistas - 2022.01

### Daniel Cabral Arnaud

|**Tipo de Projeto**|**Qtde. de Imagens por Classe**|**Qtde. de Classes**|
|--|--|--|
Classificação de Imagens| 75 | 4 |


### Projeto de classificação de imagens de animais, dentre eles: Cachorro, Lobo, Gato e Tigre

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens|YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **??%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
    Você deve colar aqui a saída do bloco de treinamento do notebook, contendo todas as épocas e saídas do treinamento
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

Exemplo de adição de imagem:
![Descrição](https://picsum.photos/seed/picsum/500/300)

## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

Exemplo de link: [Nome do link](google.com)

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
README.md
Exibindo README.md…
Projeto Final - Modelos Preditivos Conexionistas
Vitor Casadei
•
Ontem Editado às 12:09
100 pontos
Data de entrega: 7 de nov. 23:59
O objetivo desse projeto final é a aplicação dos conhecimentos adquiridos durante o curso para desenvolver um modelo customizado que realize a classificação de imagens ou a detecção de objetos em imagens.

Para esse projeto é necessário o uso de um dataset (conjunto de dados) criado pelo aluno. Esse dataset já foi criado em uma atividade anterior. Recomenda-se a utilização da ferramenta Roboflow para a criação e marcação do dataset.


Para o desenvolvimento do projeto, você deve:
Escolher se quer fazer uma classificação de imagens ou detecção de objetos em imagens.
A partir dessa decisão, você deve escolher um modelo apropriado (durante as aulas eu apresentei YOLOv5 e MobileNetv2, mas você é livre e incentivado a usar outro modelo).
A partir da escolha do modelo, você deve então criar um Jupyter Notebook para realizar o treinamento. Esse notebook deve ser salvo e submetido nessa atividade (falarei mais sobre isso abaixo).
Feito o treinamento, vocês precisam submeter as métricas de treinamento (pelo menos Acurácia/Precisão). Se usar Weights&Bias (https://wandb.ai/), anexar os dados de lá, caso contrário, colocar prints de análise manual.
(Bônus)
Como atividade Bônus, você deve publicar o projeto no HuggingFace (huggingface.co), estando esse modelo disponível para ser testado.
Submissão do Projeto

Para entrega desse projeto, você deve criar um repositório no GitHub (github.com). Esse repositório deve conter:
Uma pasta chamada "dataset" contendo as imagens utilizadas no treinamento
Uma pasta chamada "models" contendo o snapshot do modelo (seja o modelo exportado, seja os pesos da melhor época)
Um arquivo Jupyter Notebook contendo todo o código de treinamento e mantendo as saídas (outputs) dos blocos
Uma pasta chamada "assets" que deve conter quaisquer outras imagens ou arquivos necessários
Um arquivo "README.md". Esse arquivo deve conter diversas informações sobre o projeto. Anexo a essa atividade está disponível um modelo a ser preenchido.
A entrega do projeto deve conter somente o link do repositório do GitHub!
Cálculo da Nota

O cálculo da nota desse projeto é feito a partir da soma dos seguintes critérios (com limite 10):
3 pontos: Jupyter Notebook (com uma tentativa de treinamento)
5 pontos: Modelo treinado com ao menos 50% de acurácia/precisão
2 pontos: Modelo treinado com 80% ou mais de acurácia/precisão
2 pontos: Modelo publicado no HuggingFace
Você deve perceber que a somatória dos pontos atinge 12 pontos, isso é proposital: dessa forma, você pode falhar em algum critério e compensar com outro. Perceba que a atividade bônus de publicação do projeto no HugginFace pode lhe dar 2 pontos!

Assim, a nota máxima será a somatória dos pontos, com limite 10.

Deadline

O período para a conclusão desse projeto é de 1 semana a partir da finalização das aulas.

Dúvidas: vc@cesar.school ou vitor.casadei@gmail.com

README.md
Texto
1 comentário para a turma

Vitor Casadei12:22
Image Augmentation: 
- https://towardsdatascience.com/top-python-libraries-for-image-augmentation-in-computer-vision-2566bed0533e
- https://github.com/albumentations-team/albumentations
- https://github.com/mdbloice/Augmentor
