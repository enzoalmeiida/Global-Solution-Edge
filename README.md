# Global-Solution-Edge

Sistema de Monitoramento Ambiental com ESP32
Este projeto visa criar um sistema de monitoramento ambiental utilizando um microcontrolador ESP32.
O sistema é capaz de monitorar a qualidade do ar e as condições ambientais, exibindo os resultados em um display LCD. Ele utiliza um sensor de gás para medir a concentração de partículas por milhão (PPM) no ar e um sensor de temperatura e umidade para monitorar as condições ambientais.

Funcionalidades
-Medição da concentração de PPM no ar.
-Monitoramento da temperatura e umidade ambiente.
-Exibição dos resultados em tempo real em um display LCD.
-Alerta sonoro em caso de detecção de poluição.

O que foi usado.
-Microcontrolador ESP32.
-Sensor de gás (MQ-135 ou similar).
-Sensor de temperatura e umidade (DHT22 ou similar).
-Display LCD I2C 16x2.

Como Montar
Monte o circuito conforme o esquema de conexões fornecido.
Carregue o código monitoramento_ambiental_ESP32.ino para o ESP32 utilizando a IDE Arduino.
Conecte o ESP32 ao computador via USB para monitorar os resultados no Monitor Serial.

Conexões
Sensor de gás: conecte ao pino analógico 4 (PPM_PIN).
Sensor de temperatura e umidade: conecte ao pino digital 5 (DHT_PIN).
Display LCD I2C: conecte aos pinos SDA e SCL do ESP32.

Observações
Certifique-se de calibrar o sensor de gás de acordo com as especificações do fabricante para obter resultados precisos.
Este projeto pode ser expandido adicionando mais sensores para monitorar outras variáveis ambientais, como luminosidade ou qualidade do ar.
Ajuste os valores de delay conforme necessário para atender aos requisitos do seu projeto.

Benefícios
Este projeto oferece uma solução prática e eficaz para monitoramento ambiental em tempo real. Ele é útil para compreender melhor as condições do ambiente natural
e como as mudanças climáticas podem afetar ecossistemas específicos. Além disso, fornece dados valiosos para pesquisadores e cientistas que estudam ecologia, conservação da natureza e mudanças climáticas.

Autores 
Enzo Almeida Santos Ramos RM556900
Gabriel Mello RM554421
