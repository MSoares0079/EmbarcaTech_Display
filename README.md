# Display
Este projeto tem como objetivo verificar e testar o funcionamento de um display do Raspberry Pi Pico W que se comunica através de I2C.

## Como baixar e executar o código
    1-Baixar ou utilizar git clone no repositório.
          git clone https://github.com/MSoares0079/EmbarcaTech_Display.git
    2-Ter o VS Code instalado e devidamente configurado.
    3-Ter a extensão do Raspberry Pi Pico instalada no VS Code.
    4-Compilar o arquivo "Display.c" utilizando o compilador do Raspberry Pi Pico.
    5-O código pode ser simulado pelo "diagram.json" apartir da extensão Wokwi,
        mas caso deseje utilizar em um Raspberry Pi Pico W, especificamente o disponibilizado pelo EmbarcaTech,
        é necessário alterar determinada função responsável por capturar a tecla digitada.

## Estrutura do código

O código consiste em esperar o usuário digitar uma letra do teclado, no qual é reproduzida no display. Porém caso seja um número(0-9) o mesmo também é reproduzido na matriz de LEDs. 
Também existem funcionalidades aos botões A e B, no qual alteram,respectivamente, os estados dos LEDs Verde e Azul.

## Vídeo demonstrativo
(VS Code)
https://drive.google.com/file/d/10y0XzDUuFtX6mCoiX_lSLUswvD4173CW/view?usp=sharing

(BitDogLab)
https://drive.google.com/file/d/11NpK7WCTl2DMWgZshr4UJ95F-Ja20ieI/view?usp=sharing
