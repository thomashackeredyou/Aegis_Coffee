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
| Arduino Mega 2560                         | 1              | $75.00     | [Link]([https://www.ram-e-shop.com/ar/shop/rpi-phat-io-exp-io-expansion-hat-for-raspberry-pi-5-4b-3b-8267](https://www.amazon.eg/-/en/DIY-Kit-Arduino-Mega-Microcontroller-Rev3/dp/B0D7WG8BZF)) |
| Custom I/O Expansion Shield for Arduino Mega                      | 1              | $21.00     | [Link]([https://www.ram-e-shop.com/ar/shop/rpi5-board-4gb-raspberry-pi-5-4gb-8882](https://www.ram-e-shop.com/ar/shop/rpi-phat-io-exp-io-expansion-hat-for-raspberry-pi-5-4b-3b-8267)) |
| MQ-135 Air Quality Sensors                 | 5              | $9.50      | [Link](https://www.ram-e-shop.com/ar/shop/kit-mq135-mq-135-sensor-air-quality-sensor-hazardous-gas-detection-module-7312) |
| DS18B20 Temperature Sensor	                   | 1          | $10.40	      | [Link](https://www.amazon.eg/-/en/DHT11-Digital-Temperature-Humidity-Sensor/dp/B0FD2JXFBF/) |
| 12V Axial Fans                  | 2              | $28.00	     | [Link](https://www.amazon.eg/-/en/High-Efficiency-92mm-San-Ace-9G0912P2G041/dp/B0FH273YG9/) |
| 12V Servo-Controlled Flow Valve                     | 1             | $30.00	      | [Link](https://www.amazon.eg/-/en/DIY-Kit-12Vdc-Solenoid-Valve-Copper/dp/B0DDPQ5FYF) |
| NH₃	            | 500ml              | $11.75	      | [Link](https://www.flinnsci.com/ammonium-hydroxide-solution-3-m-500-ml/a0193/) |
| ZnCl₂	    | 500mg              | $22.90	      | [link](https://www.scientific-labsupplies.com/product/zinc-chloride-anhydrous-zncl2-500-grams/) |
| Solar Adapter	             | 1              | $11.00      | [link](https://ar.aliexpress.com/item/1005009299578068.html?) |
| LiFePO₄ Battery	     | 2              | $24.00      | [link](https://ar.aliexpress.com/item/1005009150241001.html?) |
| Waterproof Enclosure & Mounting Hardware               | 2              | $10.00	     | [Link](https://ar.aliexpress.com/item/1005007333668841.html?) |
| LCD Display Module (1602 I²C)	                      | 1           | $5.00      | [Link](https://ar.aliexpress.com/item/1005006493977614.html?) |
| Breadboard & Wire Kit	                 | 1              | $22.00      | [Link](https://ar.aliexpress.com/item/1005009234815336.html?) |
| PJumper Wires + Cable Glands	      | 1              | $6.00      | [Link](https://www.amazon.eg/-/en/Breadboard-Jumper-Preformed-Assorted-Tweezers/dp/B09SW8CSF6/) |
| Power Switch / Fuses & Connectors Kit       | 1              | $6.00      | [Link](https://www.amazon.eg/-/en/Plug-Fuses-15A-100-pieces/dp/B0968X7RF5/) |
| Miscellaneous Mounts Filters & Seals	       | 1              | $7.51     | [Link](https://ar.aliexpress.com/item/1005007131594877.html?) |



**Total Cost: $300.06**
