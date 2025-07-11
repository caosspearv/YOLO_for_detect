# YOLO_for_detect
Material de instrução de uso da ferramenta YOLO voltada para detecção de objetos com foco no treinamento da ferramenta.
## Obtendo a ferramenta
Site oficial: https://github.com/ultralytics/ultralytics -- examples/tutorial.ipynb
Forma rápida: pip install ultralitycs
## Dicas prévias de utilização
No colab, utilizar ambiente de exeução _GPU:T4_
## Fontes de imagens
### Pack de imagens prontas
- [roboflow](https://roboflow.com/)
  - Nem todos os dataset são de boa qualidade e o treinamento pode não ser efetivo.
  - O melhor dataset que encontrei foi este https://universe.roboflow.com/roboflow-100/vehicles-q0x2v/dataset/1/download
### Para imagens próprias: Label Studio
- instalar anaconda: https://www.anaconda.com/download
- depois de instalado, abrir *Anaconda prompt* e seguir os comandos:
  - create --name yolo-env1 python=3.12 #criação de ambiente python para o YOLO
  - conda activate yolo-env1
  - pip install label-studio
  - label-studio start
  - Exportar modelo: YOLO with images
Após iniciado, será aberto o site do label studio de forma local, não será uma plataforma online. Com isso, clique em _sign up_ e em email e senha usar _fake@fake.com_ e _fakepassword_.

## Treinamento
O git possui dois arquivos jupter que podem ser abertos no google colab para realização do treinamento do YOLO.
- Tutorial_Yolo_FromSource.ipynb: Arquivo tirado do site ofcial com algumas modificações para utilização de data-set já prontos (roboflow)
- Train_YOLO_OwnModels.ipynb: Arquivo para quem quiser criar seu próprio pack de imagens (Label-Studio) para uma aplicação específica ou que não encontrar um data-set alinhado ao objetivo de uso.
