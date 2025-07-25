# 🤖 Wi-Fi Robot Car with NodeMCU (Remote Control + Buzzer + LED + OTA)

This project is a smart Wi-Fi-controlled robot car using *NodeMCU (ESP8266)* and *L298N Motor Driver*. You can control the car from a phone browser or Android app, with features like buzzer, light, speed control, OTA update, and more!

---

## 📦 Components Used

- NodeMCU ESP8266
- L298N Dual Motor Driver
- 4x DC Motors (or 2x for basic)
- Chassis + Wheels
- 1x Active Buzzer
- 1x Super Bright LED
- Power supply (Battery 6–12V)
- Jumper Wires

---

## ⚙ Features

✅ Remote control via phone browser  
✅ Forward / Backward / Left / Right / Stop  
✅ Diagonal movements  
✅ Horn control using buzzer  
✅ Headlight ON/OFF  
✅ Speed control (10 levels)  
✅ OTA (Over-The-Air) firmware update  
✅ Auto Wi-Fi Station or AP mode fallback

---

## 🧠 Code Highlights

- Uses ESP8266WebServer for HTTP interface
- Command string received as State
- Supports speed control via levels 0 to q (330–1023 PWM)
- OTA update enabled via ArduinoOTA

---

## 🧭 Controls (via HTTP)

| Command | Action             |
|---------|--------------------|
| F       | Forward            |
| B       | Backward           |
| L       | Turn Left          |
| R       | Turn Right         |
| G       | Forward Left       |
| H       | Backward Left      |
| I       | Forward Right      |
| J       | Backward Right     |
| S       | Stop               |
| V       | Beep Horn (Buzzer) |
| W       | Turn LED On        |
| w       | Turn LED Off       |
| 0 - q   | Speed control      |

---

## 📲 How to Use

1. Open Arduino IDE
2. Install ESP8266 board via Board Manager
3. Upload the wifi_car.ino sketch
4. Open Serial Monitor to get the IP address
5. Use browser or app (like Bluino) to control car

---

## 🗂 Pin Connections

| Component      | NodeMCU Pin |
|----------------|-------------|
| Motor ENA      | D1          |
| Motor IN1      | D2          |
| Motor IN2      | D3          |
| Motor IN3      | D4          |
| Motor IN4      | D5          |
| Motor ENB      | D6          |
| Buzzer         | D7          |
| LED Light      | D8          |
| Wi-Fi Indicator| D0          |

---

## 🧪 Tested With

- Bluino Android App  
- Chrome / Safari mobile browser  
- Arduino IDE 1.8+  
- OTA update via Wi-Fi

---

## 📸 Demo

(Add a demo video or image here)  
For full step-by-step guide, visit:  
🔗 [Instructables by Bluino](https://www.instructables.com/member/bluino_electronics/)

---

## 🙋‍♂ Author

Made with ❤ by *Mohan Chetta*  
Electronics & IoT Enthusiast | 2nd Year ECE  
🔗 GitHub: [your-profile-link]

---

## 📃 License

MIT License – Free to use, modify, and share for educational & personal use.
