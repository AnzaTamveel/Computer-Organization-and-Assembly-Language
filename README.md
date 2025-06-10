# 🌃 Smart IoT Street Light System – MASM + ESP32 Integration

An intelligent street lighting solution combining low-level hardware control using **MASM (x86 Assembly)** with modern **IoT connectivity** powered by **ESP32**. This project was developed under the guidance of **Sir Syed Tehseen ul Hasan Shah** and **Ma'am Aroosh Fatima** as part of the **Computer Organization and Assembly Language (COAL)** course at the **Department of Computer Science, UET Lahore**.

---

## 🔧 Hardware Implementation

- 🌓 **LDR Sensor** – Detects ambient light levels  
- 🚗 **IR Sensor** – Detects presence of vehicles  
- 📶 **ESP32 Microcontroller** – Enables IoT capabilities via Wi-Fi  
- 💡 **Relay Module** – Controls street lights based on logic  

---

## 💻 Software Stack

- ⚙️ **MASM (x86 Assembly)** – Core logic and decision-making based on sensor inputs  
- ☁️ **ESP32 Firmware (Arduino C++)** – Handles MQTT communication  
- 📊 **Dashboard** – Monitors real-time sensor data over the network  

---

## ✨ Key Features

- 🔄 **Hybrid Architecture** – Combines low-level control with IoT communication  
- 📈 **Real-Time MQTT Streaming** – Sends LDR analog values to the server  
- 💾 **Energy-Efficient Algorithm** – Lights activate only under low-light and vehicle presence  
- 🔗 **End-to-End Hardware-Software Integration**

---

## 🚀 How It Works

1. The LDR detects ambient light; the IR sensor detects vehicle presence.
2. MASM-based logic processes sensor input on a local machine.
3. ESP32 transmits real-time LDR readings via MQTT.
4. The relay module activates or deactivates the street light accordingly.

---

## 🧠 Team & Mentorship

Developed by students of **UET Lahore – Department of Computer Science**  
Under the supervision of:  
**Sir Syed Tehseen ul Hasan Shah**  
**Ma'am Aroosh Fatima**


> ⚡ This project demonstrates the practical integration of low-level system programming and modern embedded IoT solutions.
