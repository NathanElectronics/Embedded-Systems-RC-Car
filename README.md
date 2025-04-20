# Embedded RC Car Cybertruck

An embedded systems project featuring a fully wireless RC car and controller system using four ESP32 microcontrollers. The car integrates DC and servo motor control, real-time speed tracking, and Time-of-Flight (TOF) obstacle detection. Communication between modules is handled via ESP-NOW, enabling low-latency, peer-to-peer wireless communication. The remote control features a TFT LCD display that renders both a real-time speedometer and a 2D visual map of the environment ahead of the car.

---

## 📌 Author / Contact Information

**Nathan Chan**  
Email: *nathanchan.1738@gmail.com*  
GitHub: [github.com/NathanElectronics](https://github.com/NathanElectronics)

---

## 🐞 Bug Tracker

Submit bugs or feature requests via GitHub Issues:  
[nathanchan.1738@gmail.com](nathanchan.1738@gmail.com)

---

## ⚠️ Known Issues

- TOF sensor visualization occasionally lags if multiple objects are detected in quick succession.
- ESP-NOW packet loss may occur if Wi-Fi is enabled during boot.
- TFT LCD refresh rate is fixed; dynamic scaling not yet supported.

---

## 🛠️ Build Instructions

1. Install **Arduino IDE** or **PlatformIO**.
2. Install **ESP32 Board Support** via Boards Manager.
3. Clone the repository:
   ```bash
   git clone https://github.com/nathanchan/rc-cybertruck.git
