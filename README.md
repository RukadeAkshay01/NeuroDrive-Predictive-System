# NeuroDrive-Predictive-System 🚀

### ⚙️ All-in-One Smart Motor Controller with Fault Prediction and VFD Functionality

**NeuroDrive** is a low-cost, AI-powered predictive maintenance and control system for 3-phase induction motors. It combines advanced **Motor Current Signature Analysis (MCSA)** with **Variable Frequency Drive (VFD)** logic and real-time AI-based fault detection — making it ideal for industries looking to reduce downtime and increase efficiency.

---

## 🔍 Features

- ✅ **Motor Fault Prediction** using MCSA (bearing faults, rotor issues, etc.)
- ✅ **Real-Time AI Inference** on edge (MAX78000 FEATHER BOARD)
- ✅ **Fully Functional VFD** (Speed, torque, and frequency control)
- ✅ **Predictive Alerts** via display/dashboard
- ✅ **Cost-effective** alternative to market VFDs
- ✅ **Modular Design**: Easily integrable into existing systems

---

## 📦 Project Structure

```bash
NeuroDrive/
├── firmware/              # Embedded code for motor control + sensor read
├── ai-model/              # ML model training, testing, and export
├── hardware/              # Schematic, PCB layout, BOM
├── datasets/              # MCSA datasets for fault detection
├── simulation/            # Simulink / Python-based motor simulations
├── docs/                  # Diagrams, whitepapers, documentation
├── tools/                 # CLI/GUI monitoring tools
└── README.md              # Project description
