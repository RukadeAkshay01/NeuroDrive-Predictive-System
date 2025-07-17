# ⚙️ NeuroDrive: All-in-One Smart Motor Controller with Fault Prediction and VFD Functionality

NeuroDrive is a low-cost, AI-powered predictive maintenance and control system for 3-phase induction motors. It combines advanced **Motor Current Signature Analysis (MCSA)** with **Variable Frequency Drive (VFD)** logic and **real-time AI-based fault detection** — making it ideal for industries looking to reduce downtime and increase efficiency.

---

## 🧠 Introduction: Induction Motors in Industry

Three-phase induction motors power over **70% of industrial equipment** due to their reliability, affordability, and ease of use. However, **sudden motor failures** lead to expensive downtimes.

Traditional methods like preventive maintenance often replace healthy equipment, while reactive maintenance causes unplanned stoppages. **Predictive maintenance** aims to address both issues by forecasting failures before they occur.

---

## 🛠️ Types of Maintenance

- **Reactive Maintenance** – Fix after failure; leads to long downtimes.
- **Preventive Maintenance** – Scheduled replacements; not condition-based.
- **Predictive Maintenance** – Uses sensor data to predict faults early.

---

## 📊 Why Motors Fail: Industry Statistics

| Cause                           | Approx. % of Failures |
|--------------------------------|------------------------|
| Bearing Failures               | ~40%                   |
| Stator Winding Issues          | ~30%                   |
| Rotor Bar Problems             | ~10%                   |
| Electrical Imbalances          | ~10%                   |
| Others (cooling, misalignment) | ~10%                   |

> Studies by IEEE and EPRI confirm that **MCSA** can detect a majority of these faults using just current data.

---

## ⚙️ Existing Solutions and Limitations

- **Vibration sensors**, **IR thermography**, and **ultrasound** are accurate but **costly and complex**.
- Market-available VFDs **do not support predictive monitoring**.
- Cloud-based AI systems add **latency and require connectivity**.
- Current solutions are not integrated — VFD and predictive systems are sold separately.

---

## ✅ Our Solution: NeuroDrive

**NeuroDrive** is an affordable, integrated solution that includes:

- ✔️ **MCSA-based fault detection**  
- ✔️ **On-device (Edge AI) inference** using MAX78000  
- ✔️ **Full VFD features**: Speed, direction, torque control  
- ✔️ **IoT-ready** with WiFi/LoRa for remote monitoring  
- ✔️ **Offline-capable** — no reliance on cloud  
- ✔️ **Compact and modular** hardware  
- ✔️ **Cost-effective for small to mid-scale industries**

---

## 🔧 Hardware Architecture

| Function              | Component Used                 |
|----------------------|--------------------------------|
| Main Controller       | Raspberry Pi Pico W            |
| AI Inference Engine   | ADI MAX78000FTHR               |
| Current Sensing       | ACS712 / ACS758 Hall Sensors   |
| Inverter Circuitry    | Custom MOSFET/IGBT-based VFD   |
| Power Supply          | SMPS + 5V/12V Regulation       |
| Connectivity          | WiFi + Optional LoRa           |
| Enclosure             | Compact industrial-grade case  |

---

## 💻 Software Stack

- **Model Training**: Python (scikit-learn / TensorFlow Lite)
- **Firmware**: C/C++ (ESP-IDF or Arduino IDE)
- **AI Deployment**: Quantized model on MAX78000
- **Communication**: MQTT / HTTP / UART / SPI
- **Dashboard (Optional)**: Node-RED / Grafana

---

## 🚀 Benefits & Impact

- Replaces both **traditional VFD** and **predictive units** in one box
- **No cloud** or high-end sensor dependency
- Promotes **affordable industrial automation**
- Ideal for **small- to mid-scale industries**
- Supports **"Make in India"** initiative

---

## 📚 References

- IEEE: *Motor Failure Analysis Using MCSA*  
- EPRI Reports on Predictive Maintenance  
- Analog Devices Documentation on [MAX78000](https://www.analog.com/en/products/max78000.html)  
- Research: *Predictive Maintenance using Edge AI* – IJEE  
- [AutomationWorld – MCSA Techniques](https://www.automationworld.com/motor-health)  
- [YouTube Reference Video](https://youtu.be/JwZ5ffZk-fM?si=Ku0Zh-9ZKIV3ZWgZ)

---

## 📌 Status

> This project is under active development. Contributions, feedback, and collaborations are welcome!

---

