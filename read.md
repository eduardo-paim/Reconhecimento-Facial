# Reconhecimento de Rostos na Webcam

Este é um código simples em Python que utiliza as bibliotecas OpenCV e Mediapipe para realizar o reconhecimento de rostos em tempo real por meio da webcam.

## Funcionalidade

O objetivo deste projeto é detectar e desenhar retângulos ao redor dos rostos identificados pela webcam. O código captura os frames da webcam em tempo real e utiliza a biblioteca Mediapipe para realizar o reconhecimento facial. Em seguida, desenha retângulos ao redor dos rostos identificados no frame.

## Pré-requisitos
Antes de executar o código, certifique-se de ter as seguintes bibliotecas instaladas no seu ambiente de desenvolvimento:

OpenCV: Utilizado para capturar frames da webcam e exibir a saída com os retângulos desenhados nos rostos.
Mediapipe: Utilizado para o reconhecimento facial e desenho dos retângulos nos rostos identificados.
Você pode instalar as bibliotecas usando o seguinte comando:


`pip install opencv-python mediapipe`


## Utilização

Certifique-se de ter uma webcam conectada ao seu computador.

Execute o código Python fornecido. Ele abrirá a webcam e começará a capturar os frames.

Os retângulos serão desenhados automaticamente ao redor dos rostos detectados na webcam.

Para encerrar a execução do código, pressione a tecla "Esc" ou feche a janela do vídeo.

## Aviso

Este código é apenas uma demonstração simples do reconhecimento de rostos na webcam. Ele pode não ser adequado para casos de uso mais complexos ou precisos. É recomendado explorar a documentação das bibliotecas OpenCV e Mediapipe para obter mais informações sobre as capacidades e possibilidades de configuração dessas bibliotecas.

## Recursos adicionais:

Documentação OpenCV: https://docs.opencv.org <br>
Documentação Mediapipe: https://mediapipe.dev
