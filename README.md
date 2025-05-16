# 🌱 Projeto de Monitoramento Ambiental com Arduino
 
Este projeto utiliza **Arduino** para monitorar as condições ambientais, incluindo **temperatura**, **umidade** e **luminosidade**. Com base nas medições, o sistema aciona LEDs e um buzzer para alertar sobre as condições do ambiente, exibindo as informações em um **LCD 16x2**.
 
## 📦 Componentes Utilizados
 
- 🧑‍💻 **Arduino Uno** (ou placa compatível)
- 🌡️ **Sensor DHT22** (Temperatura e Umidade)
- 🌞 **Sensor LDR** (Luminosidade)
- 💡 **LEDs**:
  - 🔴 **LED Vermelho** (alta luminosidade)
  - 🟡 **LED Amarelo** (luminosidade moderada)
  - 🟢 **LED Verde** (baixa luminosidade)
- 🔊 **Buzzer Piezoelétrico** (alerta sonoro)
- 🖥️ **Display LCD 16x2 com I2C**
 
## 🚀 Funcionalidades
 
- **Monitoração de Temperatura**: O sistema mede a temperatura e exibe no LCD, além de mostrar um alerta se a temperatura for muito baixa ou muito alta.
- **Monitoração de Umidade**: O sistema mede a umidade e alerta quando os níveis estão fora da faixa ideal (50% - 70%).
- **Luminosidade**: A luminosidade é lida via sensor LDR e o sistema aciona LEDs para indicar as condições de luz.
- **Alertas Visuais e Sonoros**: LEDs e buzzer são acionados dependendo dos níveis de luminosidade, com alertas no LCD.
 
## 🛠️ Esquema de Conexão
 
### Conexões dos Componentes:
 
1. **DHT22 (Temperatura e Umidade)**:
   - **VCC** → 5V do Arduino
   - **GND** → GND do Arduino
   - **DATA** → Pino digital 2
 
2. **LDR (Luminosidade)**:
   - Conecte um terminal ao pino **A0** do Arduino.
   - O outro terminal vai para **GND**, com um resistor de 10kΩ para formar um divisor de tensão.
 
3. **LCD I2C**:
   - **VCC** → 5V do Arduino
   - **GND** → GND do Arduino
   - **SDA** → Pino **A4** (ou conforme sua placa Arduino)
   - **SCL** → Pino **A5** (ou conforme sua placa Arduino)
 
4. **LEDs**:
   - **LED Vermelho** → Pino 13
   - **LED Amarelo** → Pino 12
   - **LED Verde** → Pino 11
   - Use resistores de **220Ω** para cada LED.
 
5. **Buzzer**:
   - **Buzzer** → Pino 7

## 👥 Integrantes do Grupo
| [<img loading="lazy" src="./img/Vitor.png" width=115><br><sub>Vitor Alcantara</sub>](https://github.com/VitorAlcantara-tech) | [<img loading="lazy" src="./img/Thiago.png" width=115><br><sub>Thiago Lima</sub>](https://github.com/thiagolima-tech) |  [<img loading="lazy" src="./img/Matheus.png" width=115><br><sub>Matheus Vasques</sub>](https://github.com/maatvasques) | [<img loading="lazy" src="./img/Marco.png" width=115><br><sub>Marco Aurélio</sub>](https://github.com/Arriatea) | [<img loading="lazy" src="./img/Bernardo.png" width=115><br><sub>Bernardo Hanashiro</sub>](https://github.com/BernardoYuji) | 
| :---: | :---: | :---: | :---: | :---: |
