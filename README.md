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
## Para imagens próprias: Label Studio
- instalar anaconda: https://www.anaconda.com/download
- depois de instalado, abrir *Anaconda prompt* e seguir os comandos:
  - create --name yolo-env1 python=3.12 #criação de ambiente python para o YOLO
  - conda activate yolo-env1
  - pip install label-studio
  - label-studio start
Após iniciado, será aberto o site do label studio de forma local, não será uma plataforma online. Com isso, clique em _sign up_ e em email e senha usar _fake@fake.com_ e _fakepassword_.
## Usando a ferramenta
Rodar o setup do jeito que veio para fazer as instalações e validar modelo.

