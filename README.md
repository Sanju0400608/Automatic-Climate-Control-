# 🌡️ Automatic Climate Control System  
**🚗 Real-Time Embedded Application using dSPACE MicroAutoBox**

Welcome to a project where **hardware meets real-world control logic**!  
This system simulates how modern vehicles maintain cabin comfort using real-time temperature monitoring and automatic actuation—built entirely on the dSPACE platform.

---

## 🧠 Project Overview

This embedded control system monitors ambient temperature and automatically regulates fan/heater output to maintain a **user-defined comfort setpoint**.

- Real-time analog input from a temperature sensor  
- Logic-based decision-making for heating or cooling  
- Live monitoring and control via **ControlDesk**

---

## 🔧 Tools & Hardware

| Component               | Description                                             |
|------------------------|---------------------------------------------------------|
| 🎛️ MicroAutoBox II     | Real-time embedded controller (DS1202)                  |
| 🧰 ConfigurationDesk   | Visual modeling of control logic and I/O configuration  |
| 📊 ControlDesk         | Real-time signal tuning, data monitoring & visualization |
| 🌡️ Temperature Sensor | Analog input to monitor ambient temperature             |
| 💡 Fan/Heater Output   | Digital outputs to simulate actuation                   |

---

## ⚙️ How It Works

### 1. 📥 Sensor Input  
A temperature sensor is wired to an analog input (e.g., AIN1), providing real-time ambient temperature data.

### 2. 🤖 Embedded Logic  
Control logic compares live input with the user-set setpoint:

| Condition       | Output Action |
|----------------|---------------|
| Too hot        | 👉 Fan ON      |
| Too cold       | 👉 Heater ON   |
| Setpoint met   | 👍 Both OFF    |

The logic is implemented in ConfigurationDesk and deployed to the MicroAutoBox.

### 3. 🧪 Real-Time Tuning  
Using ControlDesk, you can:
- Adjust setpoints on the fly  
- Monitor sensor and output signals live  
- Log data for validation

---

## 🔌 I/O Mapping Summary

| Signal          | Type            | Channel      |
|-----------------|-----------------|--------------|
| Temperature     | Analog Input     | AIN1         |
| Heater Control  | Digital Output   | DOUT1        |
| Fan Control     | Digital Output   | DOUT2        |
| Setpoint        | Tunable Variable | ControlDesk  |

---

## 🎓 Learning Outcomes

✅ Real-time embedded system modeling  
✅ Sensor integration with analog-to-digital conversion  
✅ Actuator control using digital outputs  
✅ Signal visualization and real-time system tuning  
✅ End-to-end experience with dSPACE tools

---

## 📄 License

This project is released under the [MIT License](./LICENSE).  
For academic and educational use.

---


