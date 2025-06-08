# Transformer Monitoring System

A predictive maintenance monitoring system for small transformers using real-time temperature, load current, and oil level data over wireless communication.

---

### ⚙️ Hardware Design
- Temperature + oil-level sensors
- ESP32 with Wi-Fi for MQTT updates
- OLED display + SD card for backup logging

---

### 🧠 Control/Software Features
- Sample at 1 Hz, average over 30s
- Alert when temp > 80°C or load > 85%
- Auto-backup if network fails

---

### 📊 Results (Expected)
- Detect overheating or overload events
- MQTT log via InfluxDB
- Simulated field run on bench transformer

---

### 🧰 Tools Used
- Arduino IDE (ESP32), Embedded C
- Node-RED, Grafana, MQTT
- KiCad

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
