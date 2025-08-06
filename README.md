# 🔷 Peltier-Based Liquid Cooling System

This project is a smart liquid cooling system designed using a Peltier module, non-conductive coolant, and ESP8266 to maintain optimal temperatures for servers and high-performance systems.

## 📌 Objective
To design a compact, cost-effective, and efficient cooling system using Peltier technology to replace traditional air-cooling methods in electronics and IT infrastructure.

---

## 🧰 Components Used

| Component                     | Description/Model               |
|------------------------------|----------------------------------|
| Microcontroller              | ESP8266 NodeMCU                  |
| Peltier Module               | TEC1-12706                       |
| Coolant                      | Ethylene glycol + distilled water |
| Temperature Sensor           | Waterproof DS18B20              |
| Water Pump                   | 12V Mini Pump                   |
| Heat Sink & Fan              | For heat dissipation            |
| Relay Module (removed now)   | Earlier version used this       |
| Power Supply                 | 12V/5A Adapter                  |

---

## ⚙ Working Principle

- ESP8266 reads the temperature using the DS18B20 waterproof sensor placed in coolant.
- If the temperature exceeds a defined limit, the Peltier module is activated to cool down the coolant.
- The system recirculates the coolant using a water pump, transferring heat away from electronics.
- The updated version replaces relay modules with direct control logic using GPIO.

---

## 💡 Features

- 🔌 Low power consumption
- ❄ Smart temperature control
- 🔁 Continuous liquid circulation
- 📶 ESP8266 Wi-Fi enabled (expandable for IoT monitoring)
- ✅ Cost-effective alternative to traditional cooling

---

## 🖼 Project Images

![Prototype](procom.jpg)

---

## 📂 File Structure

- Code/: Contains Arduino code for ESP8266-based temperature monitoring and Peltier control
- Documents/: Includes the final project report and component list
- Images/: Project setup and wiring diagrams
- README.md: GitHub project documentation

---

## 🧠 Applications

- Server room cooling
- Computer/PC cooling
- IoT-based thermal management
- Heat-sensitive device enclosures

---

## 📘 Project Report

For detailed technical explanation, refer to:
📄 [code for system.pdf)

---

## 🚀 Future Enhancements

- Add IoT Dashboard for remote monitoring
- Use MOSFET-based control for faster switching
- Integrate battery backup and power efficiency algorithm

---

## 👨‍💻 Developed By

Mohammad Tanzil Dilawar Mestri,
Ahmed Bidiwale,
Amaan Ansari
Electronics and Communication Engineering  
KLS VDIT, Haliyal — 2026 Batch

---

## ⭐ GitHub Link (after uploading)# 🔷 Peltier-Based Liquid Cooling System

This project is a smart liquid cooling system designed using a Peltier module, non-conductive coolant, and ESP8266 to maintain optimal temperatures for servers and high-performance systems.

## 📌 Objective
To design a compact, cost-effective, and efficient cooling system using Peltier technology to replace traditional air-cooling methods in electronics and IT infrastructure.

---

## 🧰 Components Used

| Component                     | Description/Model               |
|------------------------------|----------------------------------|
| Microcontroller              | ESP8266 NodeMCU                  |
| Peltier Module               | TEC1-12706                       |
| Coolant                      | Ethylene glycol + distilled water |
| Temperature Sensor           | Waterproof DS18B20              |
| Water Pump                   | 12V Mini Pump                   |
| Heat Sink & Fan              | For heat dissipation            |
| Relay Module (removed now)   | Earlier version used this       |
| Power Supply                 | 12V/5A Adapter                  |

---

## ⚙ Working Principle

- ESP8266 reads the temperature using the DS18B20 waterproof sensor placed in coolant.
- If the temperature exceeds a defined limit, the Peltier module is activated to cool down the coolant.
- The system recirculates the coolant using a water pump, transferring heat away from electronics.
- The updated version replaces relay modules with direct control logic using GPIO.

---

## 💡 Features

- 🔌 Low power consumption
- ❄ Smart temperature control
- 🔁 Continuous liquid circulation
- 📶 ESP8266 Wi-Fi enabled (expandable for IoT monitoring)
- ✅ Cost-effective alternative to traditional cooling

---

## 🖼 Project Images

![Prototype](procom.jpg)

---

## 📂 File Structure

- Code/: Contains Arduino code for ESP8266-based temperature monitoring and Peltier control
- Documents/: Includes the final project report and component list
- Images/: Project setup and wiring diagrams
- README.md: GitHub project documentation

---

## 🧠 Applications

- Server room cooling
- Computer/PC cooling
- IoT-based thermal management
- Heat-sensitive device enclosures

---

## 📘 Project Report

For detailed technical explanation, refer to:
📄 [code for system.pdf)

---

## 🚀 Future Enhancements

- Add IoT Dashboard for remote monitoring
- Use MOSFET-based control for faster switching
- Integrate battery backup and power efficiency algorithm

---

## 👨‍💻 Developed By

Mohammad Tanzil Dilawar Mestri,
Ahmed Bidiwale,
Amaan Ansari
Electronics and Communication Engineering  
KLS VDIT, Haliyal — 2026 Batch
