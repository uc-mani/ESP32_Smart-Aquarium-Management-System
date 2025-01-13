# Smart-Aquarium-Management-System
The Integrated Smart Aquarium Management System projects aims to automate functions within an aquarium to ensure optimal conditions for aquatic life.

Using ESP32 as central Hub, it integrated four key subsystems:
1. Water Quality Monitoring and Control
2. Automated Feeding System
3. Lighting Control System
4. Filteration and Cleaning System
5. Data Logging and Monitoring


![WhatsApp Image 2025-01-13 at 8 10 12 PM](https://github.com/user-attachments/assets/6cd6b264-8d50-4bce-b18b-73d742a9e335)



https://github.com/user-attachments/assets/fc7ca827-6a42-4b8f-9831-d93c1e3367cb



**Functionality**
- The Water Quality Contorl system monitors PH, temperature and oxygen levels using following sesnsors: TDS and Temperature sensors.
- While the filteration and cleaning system will be triggered via the indication from Turbidity sensor which tells the clarity of water.
- The Automated feeding system dispense food at regular intervals using servo motor and feeding jar.
- The lighting system is controled via LDR attached to the ESP32 and an LED strip, to make sure aquarium light is adjusted according to the surrounding light.
- To maiantain the optimal temperature, a heater is attached via relay which is controlled from temperature sensor values.
- Similarly a motor is attached with Relay to supply air and clean water when required as indicated by turbidity sensor values.
- Additionally real time logging on the BLYNK web and mobile interface, allows user to monitor aquarium stats, enhancing the aquarium ecosystem.


![WhatsApp Image 2025-01-13 at 8 14 44 PM](https://github.com/user-attachments/assets/aec47bdd-8947-4072-bca1-1f54454250d7)

- Code Snipet
![1](https://github.com/user-attachments/assets/31f12306-75c5-4ea7-b6da-b9796883a56b)


- Mobile App Interface

![WhatsApp Image 2025-01-13 at 8 09 45 PM](https://github.com/user-attachments/assets/e5368753-9d8d-47f8-8cfa-80748fe6ad66)


- LED OFF via LDR
![2](https://github.com/user-attachments/assets/61c50071-079f-4b13-b144-a6433366bbea)


- LED ON via LDR
![3](https://github.com/user-attachments/assets/40c16eb5-b3b4-407f-900c-258bbb1eb5ab)

- Automated Feeding
  
https://github.com/user-attachments/assets/9abb6c2e-9bc7-4309-a281-6388c265da59

