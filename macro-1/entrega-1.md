Relatório referente à Macro Entrega 1 - 17/12/2020

> Responsável pela entrega: Osvaldo da Silva Neto



1. **Lista dos equipamentos:**

- ESP8266 nodemcu

- Sensor capacitivo de umidade do solo YL-69

- Sensor de temperatura DHT-11

  

2. **Descrição**

   2.1 - **ESP8266 nodemcu**

   <p align="center">
    <img src="./img/node.png" alt="alt text" width="196" height="196">
   </p>  

   ​         Este dispositivo será responsável por interme diar a comunicação entre os sensores e a aplicação web. Nele será feita toda a lógica de captura e processamento dos dados para posteriormente serem encaminhados para uma API que fará o tratamento e armazenamento dos dados em banco. A escolha deste módulo se deu por sua eficiência, baixo custo, por possuir uma interface de comunicação wifi integrada  além de pinos analógicos que simplificam a integração de todo o sistema evitando a aquisição e configuração de hardwares adicionais.

   

   2.2 - **Sensor** **capacitivo de umidade do solo YL-69**

   <p align="center">
      <img src="./img/yl69.png" alt="alt text" width="196" height="196">
   </p>


   Este dispositivo será responsável pela leitura da umidade do solo, conectado ao módulo ESP8266



   2.3 - **Sensor DHT-11**

   <p align="center">
      <img src="./img/dht.png" alt="alt text" width="159" height="159">
   </p>

   ​Este sensor será responsável por capturar as variações de           temperatura e umidade do ambiente e será conectado ao módulo de transmissão ESP8266 para integração com o sistema.

​