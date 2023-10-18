## Portfólio Lucas Mirachi
[banner]: ./banner.png "banner"
[ocultador]: ./imgs/ocultador.png "ocultador"
[ocultador2]: ./imgs/ocultador2.png "ocultador2"
[face1]: ./imgs/face1.png "face1"
[face3]: ./imgs/face3.png "face3"

![][banner]
<sub>*Buscando cada vez mais aprendizado em Visão Computacional | Inteligência Artifical | Automação | Ciência dos Dados</sub>

Este é um repositório com meu portfólio, que contempla os principais projetos que desenvolvi, além  dos que estou trabalhando atualmente.

**Background em:** Python, SQL, C++, Machine Learning, Deep Learning e Softwares de Análise de Dados (Tableau, StreamLit e PowerBI).

**Links:**
* [LinkedIn](https://www.linkedin.com/in/lucasmirachi)
* [Medium](https://medium.com/@lucas.mirachi)

---

## Projetos Visão Computacional
### **Controle de Volume por Gestos** -> [Link para repositório](https://github.com/lucasmirachi/gesture-volume-control)
* **Resumo**:Desenvolvi um projeto para controlar o volume de um sistema Linux usando gestos de mão. Utilizei a câmera para capturar os gestos, e com técnicas de visão computacional, mapeei os gestos para ajustar o volume do áudio em tempo real. Oferecendo uma maneira intuitiva e sem dispositivos físicos de controlar o volume.
* **Tecnologias**: Python3 e [Mediapipe](https://developers.google.com/mediapipe)
<p align="center">
<img src="https://github.com/lucasmirachi/gesture-volume-control/raw/main/images/gesturevolumecontrol.gif" width="50%" />
</p>

### **Face Mesh** -> [Link para repositório](https://github.com/lucasmirachi/face-mesh)
* **Resumo**: Neste projeto, criei um sistema de face mesh que mapeia várias áreas da face do usuário em tempo real usando visão computacional. Utilizei uma câmera para capturar a imagem facial e identificar características como olhos, nariz e boca, possibilitando aplicações como reconhecimento facial e análise de expressões.
* **Tecnologias**: Python3 e [Mediapipe](https://developers.google.com/mediapipe)
<p align="center">
<img src="https://github.com/lucasmirachi/face-mesh/blob/main/images/FaceMesh.gif" width="50%" />
</p>


### **Hand Tracking** -> [Link para o repositório](https://github.com/lucasmirachi/hand-tracking)
* **Resumo**: Criei um projeto em Python3 usando a biblioteca Mediapipe para rastrear e reconhecer gestos de mãos em tempo real. O sistema captura a entrada da câmera e mapeia pontos-chave nas mãos, permitindo interações baseadas em gestos com o computador.
* **Tecnologias**: Python3 e [Mediapipe](https://developers.google.com/mediapipe)
<p align="center">
<img src="https://github.com/lucasmirachi/hand-tracking/raw/main/images/handtracking.gif" width="50%" />
</p>


### **Contador de dedos** -> [Link para o repositório](https://github.com/lucasmirachi/finger-counter)
* **Resumo**: Criei um projeto em Python3 usando a biblioteca Mediapipe para contar os dedos detectados em tempo real. O sistema utiliza a câmera para capturar a mão e, por meio do rastreamento de pontos, determina o número de dedos levantados. Uma aplicação prática desse projeto poderia ser um auxiliar em salas de aula, onde o professor pode usar gestos para fazer contagens interativas durante atividades educacionais.
* **Tecnologias**: Python3 e [Mediapipe](https://developers.google.com/mediapipe)
<p align="center">
<img src="https://github.com/lucasmirachi/finger-counter/raw/main/finger_counter.gif" width="50%" />
</p>


### **Detector de Faces** -> [Link para o repositório](https://github.com/lucasmirachi/Face-Detection)
* **Resumo**: Neste projeto, vou explorar a detecção facial usando Cascata de Haar. No entanto, é importante observar que este é um algoritmo de detecção facial, e não de reconhecimento facial. Ele analisará uma imagem e dirá "sim, é um rosto" ou "não, não há rosto nesta imagem", sem identificar a quem esse rosto pertence.
* **Tecnologias**: Python3 e OpenCV (Haar Cascade Classifier)

| <img src="https://github.com/lucasmirachi/Face-Detection/blob/main/images/don-corleone.png" width="50%" /> | ![][face1] |
| --------------------------------- | --------------------------------- |
| <img src="https://github.com/lucasmirachi/Face-Detection/raw/main/images/brazil-selection.png" />|![][face3]|

### **Detector de Cores** -> [Link para o repositório](https://github.com/lucasmirachi/Color-Detector)
* **Resumo**: Neste projeto, criei um sistema que detecta cores em tempo real usando processamento de imagem e visão computacional. Através da câmera, identificamos cores específicas, permitindo aplicações como rastreamento de objetos coloridos e automação baseada em cores.
* **Tecnologias**: Python3 e OpenCV.
<p align="center">
<img src="https://github.com/lucasmirachi/Color-Detector/blob/main/output.gif?raw=true" width="25%" />
</p>

### **Ocultador de placas de veículos** -> [Link para o repositório](https://github.com/lucasmirachi/License-Plate-Blurring/blob/main/plate-blurring.ipynb)
* **Resumo**: Desenvolvi um programa em Python usando OpenCV para processar imagens de carros. O programa detecta automaticamente a placa do veículo e aplica um desfoque para garantir a privacidade das identificações.
* **Tecnologias**: Python3 e OpenCV

| ![][ocultador] | ![][ocultador2] |
| --------------------------------- | --------------------------------- |


---

## Projetos Veículos Autônomos

Como parte do curso de Nanodegree de Veículos Autônomos da Udacity, adquiri conhecimentos e desenvolvi projetos nas seguintes áreas:

- Perception Engineering: Utilizando técnicas de Visão Computacional com OpenCV, criei algoritmos que vão desde a detecção simples de faixas de tráfego até desafios mais complexos, como detecção de objetos em movimento e percepção do ambiente usando Lidar.

- Deep Learning: Compreendi conceitos de Aprendizado Profundo, como Redes Neurais Profundas e Redes Neurais Convolucionais (CNNs), e construí um classificador de placas de trânsito, além de um algoritmo de Clonagem Comportamental que aprende a dirigir utilizando habilidades do usuário em um simulador de direção.

- Sensor Fusion e Mapeamento/Localização: Aprendi a utilizar conceitos como Filtro de Kalman e Filtro de Kalman Estendido para integrar diferentes sensores com frequências distintas e compreender como podem trabalhar juntos para solucionar problemas de mapeamento e localização.

- Engenharia de Controle: Adquiri conhecimentos sobre a tecnologia usada para controlar sistemas robóticos/automotivos, com ferramentas como Controladores PID e ROS (Sistema Operacional de Robôs). 


###**Link para os projetos**:
* Projeto de identificação de Faixas de Trânsito Simples: [link](https://github.com/lucasmirachi/CarND-LaneLines-P1/blob/master/writeup.md)

<p align="center">
<img src="https://github.com/lucasmirachi/CarND-LaneLines-P1/raw/master/examples/non_blinking_lines.gif" width="50%" />
</p>
* Identificação Avançada de Faixas de Trânsito e angulação da estrada:  [link](https://github.com/lucasmirachi/CarND-Advanced-Lane-Lines) 

<p align="center">
<img src="https://github.com/lucasmirachi/CarND-Advanced-Lane-Lines/blob/main/images_writeup/advanced_lane_finding.png?raw=true)" width="50%" />
</p>
* Projeto de Behavioral Cloning para simulação de um veículo autônomo em pista: [link](https://github.com/lucasmirachi/CarND-Behavioral-Cloning-P4)

<p align="center">
<img src="https://github.com/lucasmirachi/CarND-Behavioral-Cloning-P4/raw/master/writeup_imgs/after_balancing.gif" width="50%" />
</p>

* Simulação de Path Planning de um veículo autônomo em uma estrada: [link](https://github.com/lucasmirachi/CarND-Path-Planning-Project/blob/main/writeup.md)

<p align="center">
<img src="https://github.com/lucasmirachi/CarND-Path-Planning-Project/raw/main/writeup_imgs/path-planning-final.gif" width="50%" />
</p>

* Classificador de placas de trânsito com Deep Learning: [link](https://github.com/lucasmirachi/CarND-Traffic-Sign-Classifier)

![Classificador de Placas de Trânsito](https://github.com/lucasmirachi/CarND-Traffic-Sign-Classifier/raw/main/examples/augmented.png)

* Projeto de localização de veículo por filtros de partículas: [link](https://github.com/lucasmirachi/CarND-Kidnapped-Vehicle-Project)

* Projeto de Kalman Filter Extendido: [link](https://github.com/lucasmirachi/CarND-Extended-Kalman-Filter-Project)

* Projeto Final: [link](https://github.com/lucasmirachi/CarND-Capstone-Project)

#### Work In Progress: [AWS Deep Racer](https://github.com/lucasmirachi/Model-Training-AWS-DeepRacer-)
<p align="center">
<img src="https://camo.githubusercontent.com/2b40ae356023483f7ee7139a05c77d7390236c2c0a949c9da5c55615a16c6e99/68747470733a2f2f64312e6177737374617469632e636f6d2f72323031382f722f53696c76657273746f6e652f4465657052616365725f4368726f6d655f536d616c6c5f7267622e616139623261336265653634646165326435393365626637343133333237376232383131613432652e706e67" width="20%" />
</p>


---

## Projetos Ciência dos Dados

* **Sistema de recomendação de produtos - Estudo simulação em uma loja de e-commerce:** https://bit.ly/3wyXBlK
* **Análise exploratória de uma loja de varejo e-commerce com Python e Pandas:** https://bit.ly/3Jh03oo
* **Estudo e análise de retenção de funcionários de uma empresa fictícia com Machine Learning:** https://bit.ly/3kNufxr
* **Análise de dados de autonomia de combustível utilizando Seaborn (Google Colab):** https://bit.ly/30GTeFq
* **Exploração e análise de dados com Streamlit (uma alternativa 100% OpenSource ao Tableau e Power BI):** https://bit.ly/2Fgbo9O
* **Conectando um Fiat Palio na Nuvem AWS (Work in Progress!):** https://bit.ly/2I8pICg
* **Projeto de Visão computacional - Implementação de algoritmo de Hand Tracking com Python e Mediapipe:** http://bit.ly/3WAQHad
* **Algoritmo simplificado de detecção de objetos utilizando Template Matching e OpenCV:** http://bit.ly/4043K6T
* **Implementação de um algoritmo de Behavioural Cloning (Projeto de Deep Learning Avançado): ** http://bit.ly/3HAEEoW
* **Algoritmo de Inteligência Artifical para detecção de placas de trânsito : ** http://bit.ly/403KZjX
* **Simulação de um projeto de controle de qualidade em uma "fábrica de cubos mágicos" - Projeto de Image Classification e Object Tracking:** https://bit.ly/3nveTdN
<p align="center">
<img src="https://github.com/lucasmirachi/cubo_magico/raw/master/spoiler.png" width="35%" />
</p>
* **Automatizando o Instagram com Python (Medium):**
* **Image Classification para classificar placas de trânsito com Deep Learning:** https://bit.ly/30I1FAx
* **Detecção de faixas de trânsito com OpenCV:** https://github.com/LucasMirachi/Lane_Detection
![](https://raw.githubusercontent.com/LucasMirachi/Lane_Detection/master/Images/detected_avg_lines.gif)