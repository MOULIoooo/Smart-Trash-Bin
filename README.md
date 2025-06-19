# Smart-Trash-Bin
# 🗑️ Smart Trash Bin with IoT & Waste Classification

This project presents an IoT-enabled Smart Trash Bin that improves waste management by automatically monitoring bin levels and classifying waste. It includes user identification using RFID/NFC tags, real-time space monitoring using ultrasonic sensors, and IoT-based alerts to authorities when the bin is full. The system also segregates waste into recyclable and biodegradable categories for efficient processing.

---

## 📌 Components Used

- Arduino Uno / ESP32
- Ultrasonic Sensor (HC-SR04) – for bin fill-level
- RFID Module (RC522) – for user identification
- Servo Motor – for automated lid or waste segregation
- Load Cell or IR Sensors – optional for waste weight/detection
- Wi-Fi Module (ESP8266/ESP32) – for IoT integration
- Buzzer / LED Indicators
- Power Supply, Breadboard, Wires

---

## ⚙️ Working Principle

1. **RFID tag scan** identifies the user.
2. **Ultrasonic sensor** measures bin fullness.
3. If the bin is full:
   - **Buzzer/LED alerts**
   - IoT module sends data to authorities.
4. **Servo motor** separates waste based on sensor input (e.g., wet vs dry).
5. **Data dashboard** shows real-time bin status remotely.

---

## 🔧 How to Use

1. Power the device and scan a valid RFID tag.
2. Drop waste into the bin; the ultrasonic sensor checks the level.
3. Once full, the system notifies via Wi-Fi or GSM.
4. Waste is sorted automatically and data is logged.

---

## 📸 Project Images

*Add photos of the working model and wiring.*

---

## 📹 Demo Video

[Watch the demo](https://your-demo-link)

---

## 🧠 Developed By

👨‍💻 Mouli S  
St. Joseph's College of Engineering  
Department of EEE
