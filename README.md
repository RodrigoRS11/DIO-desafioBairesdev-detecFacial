# **DIO-desafioBairesdev-detecFacial**

O objetivo principal deste projeto é aplicar as bibliotecas e frameworks estudados ao longo das aulas, com foco no desenvolvimento de um sistema de detecção e reconhecimento de faces. Utilizando o framework **TensorFlow** em conjunto com as bibliotecas que forem consideradas adequadas pelo projetista, a proposta visa explorar as capacidades do aprendizado de máquina para identificar e classificar faces em imagens de forma eficaz.

Detecção de Faces: Para a detecção, será utilizada uma rede neural treinada para localizar as faces na imagem. Isso pode ser feito por meio de redes como o **MTCNN (Multi-task Cascaded Convolutional Networks)**, que é amplamente utilizada para a detecção de faces em tempo real ou imagens.

Classificação das Faces Detectadas: A rede de detecção foi utilizada para localizar as faces na imagem, e em seguida, as faces detectadas foram submetidas a uma rede de classificação para determinar a identidade da pessoa. Para isso, foi feita um transfer learning no modelo **VGG16** com o conjunto de dados específico da tarefa. Esse processo permitiu que o modelo aprendesse as características essenciais para identificar as faces corretamente, mantendo a precisão e a eficiência, sem a necessidade de treinamento completo desde o início.

## **Resultado**

![Exemplo](https://raw.githubusercontent.com/RodrigoRS11/DIO-desafioBairesdev-detecFacial/refs/heads/main/1.png)

O objetivo deste projeto era identificar os rostos dos membros da família da série Todo Mundo Odeia o Chris, com foco em reconhecer exclusivamente os pais como autorizados pelo sistema. A ideia seria aplicar esse reconhecimento em um sistema de segurança, como o controle de acesso a um cofre ou outro local privado. No entanto, se o sistema fosse destinado a um cofre, é provável que o Julius preferisse ser o único com acesso
