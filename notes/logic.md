# Pseudocode – Transformer Monitoring System

## Goal
Continuously monitor temperature and vibration of a distribution transformer to predict failures.

## Flow
- [ ] Read temperature (e.g., DS18B20) and vibration sensor every 5 s
- [ ] Log to SD card with timestamp
- [ ] Trigger alarm if:
  - Temp > 80 °C
  - Sudden vibration spike
- [ ] Display current readings on LCD
- [ ] Push summary to cloud every 30 min (via Wi-Fi or GSM)
