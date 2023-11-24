# globalsolution-edge


**https://wokwi.com/projects/382191888917294081**


O problema de saúde abordado neste projeto fictício é a monitorização da temperatura corporal de um paciente, simulando um dispositivo IoT que coleta dados relevantes para a saúde. Em situações reais, a monitorização da temperatura corporal é fundamental para detectar febres e variações significativas que podem indicar problemas de saúde.

A solução proposta é um sistema que utiliza um ESP32 simulado no Wokwi, conectado a sensores fictícios de temperatura (simulado), umidade, luminosidade (LDR), e um sensor de gás. Esses dados são publicados em um servidor MQTT simulado para possibilitar a monitorização remota. Além disso, LEDs e um buzzer são utilizados para indicar situações críticas, como a detecção de altos níveis de gás.



1. Acesse o Wokwi:
   Acesse o [Wokwi](https://wokwi.com/arduino/simulator) e clique em "Start Simulation".

2. Cole o Código:
   Cole o código fornecido na janela do editor Arduino no Wokwi.

3. Configurações de Simulação:
   Certifique-se de que o tipo de placa esteja configurado para "ESP32". Você pode ajustar outras configurações, como a velocidade de execução da simulação.

Execução da Simulação:
   Clique em "Run" para iniciar a simulação. Isso iniciará a execução do código no ESP32 simulado.

5. Observação da Saída:
   Observe a saída no console serial para visualizar os dados simulados de temperatura, umidade, luminosidade, e gás.

6. Monitorização Remota (Opcional):
   Como parte da simulação, os dados são publicados em tópicos MQTT simulados. Se desejar, você pode usar um cliente MQTT para monitorizar esses dados simulados. Certifique-se de configurar o endereço e a porta do servidor MQTT no código, e ajuste conforme necessário.

7. Interaja com os Componentes Simulados:
   Experimente alterar os valores simulados, como temperatura e umidade, para ver como o sistema reage. Observe como os LEDs e o buzzer indicam situações críticas quando o sensor de gás detecta níveis elevados.


Esse código inclui uma função simularMedicaoTemperaturaCorporal que gera valores aleatórios de temperatura corporal entre 36.0 e 38.0 graus Celsius. Você pode ajustar essa função conforme necessário para a simulação desejada. Além disso, a simulação de umidade foi adicionada para ilustrar como isso pode ser feito.
