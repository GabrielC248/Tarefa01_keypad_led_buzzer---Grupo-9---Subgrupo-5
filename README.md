Controle de LEDs e um Buzzer com um Teclado Matricial no Raspberry Pi Pico W

Integrantes:
- Gabriel Cavalcanti Coelho (GabrielC248)
- Daniel Souza Silva (danielsva0)
- Isabel Rosa De Santana (Isabelrs02)
  
Vídeo:
- a

Este projeto demonstra como utilizar um teclado matricial 4x4 para controlar LEDs e um buzzer em uma placa Raspberry Pi Pico W. O código permite alternar os LEDs e ativar o buzzer pressionando as teclas designadas.

• Requisitos:
    
    - Raspberry Pi Pico W;
    - LEDs (vermelho, verde, azul);
    - Resistores para os LEDs;
    - Buzzer;
    - Teclado matricial 4x4;
    - Fios de conexão;
    - Protoboard;
    - SDK do Raspberry Pi Pico configurado (C/C++).

• Esquema de Conexões:
    
    • LEDs e Buzzer:
        
        - LED vermelho no pino GPIO 15;
        - LED verde no pino GPIO 14;
        - LED azul no pino GPIO 13;
        - Buzzer no pino GPIO 12.
        
    • Teclado Matricial:
        
        • Linhas:
            
            - L1 no pino GPIO 11;
            - L2 no pino GPIO 10;
            - L3 no pino GPIO 9;
            - L4 no pino GPIO 8.
        
        • Colunas:
            
            - C1 no pino GPIO 7;
            - C2 no pino GPIO 6;
            - C3 no pino GPIO 5;
            - C4 no pino GPIO 4.

• Funcionalidades:
    
    - Pressione a tecla A para alternar o estado do LED vermelho;
    - Pressione a tecla B para alternar o estado do LED verde;
    - Pressione a tecla C para alternar o estado do LED azul;
    - Pressione a tecla D para ativar o buzzer por 250ms;
