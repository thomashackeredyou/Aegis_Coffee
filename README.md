# Aegis Coffee  
Four-Chamber Urban Air Purifier Using Coffee Grounds and Smart Sensors

## Project Description  
Aegis Coffee is a four-chamber air purification unit designed to improve air quality in high-pollution environments like downtown Cairo. The system filters nitrogen oxides (NOx), sulfur oxides (SOx), volatile organic compounds (VOCs), and particulate matter (PM2.5 and PM10) using spent coffee grounds in a chemical scrubber. 

Each chamber targets a specific type of pollutant. Real-time sensors measure incoming air quality, and a Raspberry Pi 5 processes the data and controls automated solenoid valves to route the air based on pollution type. The system also supports solar power integration and displays live data on a screen.

## Why I Made This Project  
Air pollution is a serious health hazard in many cities, and traditional filtration systems are often expensive or energy-intensive. I wanted to design an efficient, cost-effective, and sustainable solution using recycled coffee grounds and open-source electronics to improve public health and reduce environmental impact.

## How the Device Works  

1. Polluted air is drawn in through the intake.
2. Sensors analyze the pollutant composition (PM, NOx, VOC, etc.).
3. Raspberry Pi receives the data and opens the appropriate solenoid valve.
4. Air flows through one of four chambers filled with chemically prepared coffee grounds tailored to remove specific pollutants.
5. Cleaned air exits the system and is monitored by a second set of sensors to verify filtration effectiveness.
6. Results are displayed on a screen and logged for analysis.

   
## Images  

![IMG-20250715-WA0069](https://github.com/user-attachments/assets/1be72757-d232-4119-b896-880591b13055)
<img width="411" height="343" alt="Aegis_SC" src="https://github.com/user-attachments/assets/3ef57fe2-f72f-4f97-8aaf-5066a96c66ec" />

<img width="496" height="330" alt="Aegis_SC (1)" src="https://github.com/user-attachments/assets/887868a3-1f37-4b50-a7ab-5e8195394642" />

## Bill of Materials (BOM)

| Component                                     | Quantity       | Price (USD) | Link |
|----------------------------------------------|----------------|-------------|------|
| HAT for Raspberry Pi                         | 1              | $19.22      | [Link](https://www.ram-e-shop.com/ar/shop/rpi-phat-io-exp-io-expansion-hat-for-raspberry-pi-5-4b-3b-8267) |
| Raspberry Pi 5 - 4GB                         | 1              | $109.27     | [Link](https://www.ram-e-shop.com/ar/shop/rpi5-board-4gb-raspberry-pi-5-4gb-8882) |
| Raspberry Pi 5 Aluminum Case                 | 1              | $7.59       | [Link](https://www.ram-e-shop.com/ar/shop/rpi5-box-aluminum-enclosure-for-raspberry-pi-5-stripe-metal-aluminum-case-9202) |
| MQ-135 Air Quality Sensors                   | 2 pcs          | $24.00      | [Link](https://www.amazon.com/dp/B07FQT8ZBZ) |
| DS18B20 Temperature Sensor                   | 1              | $10.00      | [Link](https://www.amazon.com/dp/B01DKC2GQC) |
| 12 V Axial Fans (large)                      | 2              | $28.00      | [Link](https://www.amazon.com/dp/B07PZP8NDV) |
| 12 V Servo-Controlled Flow-Valve             | 1              | $25.00      | [Link](https://www.amazon.com/dp/B07H4ZQ2QL) |
| Coffee Grounds + NH₃ + ZnCl₂ (Chemicals)     | —              | $20.00      | — |
| Solar Adapter + LiFePO₄ Battery              | 1              | $45.00      | — |
| Waterproof Enclosure + Mounting Hardware     | —              | $20.00      | — |
| LCD Display Module (1602 I²C)                | 1              | $12.00      | [Link](https://www.amazon.com/dp/B012A1PNVI) |
| Breadboard & Wire Kit                        | 1 set          | $12.00      | [Link](https://www.amazon.com/dp/B01EV70C78) |
| Jumper Wires + Cable Glands                  | —              | $10.00      | — |
| Power Switch + Fuses + Connectors Kit        | —              | $10.00      | — |

**Total Cost: $329**

