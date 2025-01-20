Controle de LEDs e um Buzzer com um Teclado Matricial no Raspberry Pi Pico W

Integrantes:
- Gabriel Cavalcanti Coelho (GabrielC248)
- Daniel Souza Silva (danielsva0)
- Isabel Rosa de Santana (Isabelrs02)
- Gabriel Neponuceno Batista (GNepoB)
- Danilo Silveira da Glória (codedanilo)
  
Vídeo:
- https://youtu.be/JK0JTlVKZd8?si=qWI01vm5uK-zqMvz

Este projeto demonstra como utilizar um teclado matricial 4x4 para controlar LEDs e um buzzer em uma placa Raspberry Pi Pico W. O código permite alternar os LEDs e ativar o buzzer pressionando as teclas designadas.

• Requisitos:
    
    - Raspberry Pi Pico W;
    - LEDs (vermelho, verde e azul);
    - Resistores para os LEDs;
    - 2 Buzzers;
    - Teclado matricial 4x4;
    - Fios de conexão;
    - SDK do Raspberry Pi Pico configurado (C/C++).

• Esquema de Conexões:
    
    • LEDs e Buzzer:
        
        - LED vermelho no pino GPIO 13;
        - LED azul no pino GPIO 12;
        - LED verde no pino GPIO 11;
        - Buzzer no pino GPIO 10;
        - Buzzer no pino GPIO 21.
        
    • Teclado Matricial:
        
        • Linhas:
            
            - L1 no pino GPIO 9;
            - L2 no pino GPIO 8;
            - L3 no pino GPIO 7;
            - L4 no pino GPIO 6.
        
        • Colunas:
            
            - C1 no pino GPIO 5;
            - C2 no pino GPIO 4;
            - C3 no pino GPIO 3;
            - C4 no pino GPIO 2.

• Funcionalidades:
    
    - Pressione a tecla A para alternar o estado do LED vermelho;
    - Pressione a tecla B para alternar o estado do LED azul;
    - Pressione a tecla C para alternar o estado do LED verde;
    - Pressione a tecla # para ativar o buzzer 1 por 250 ms;
    - Pressione a tecla * para ativar o buzzer 2 por 250 ms;
