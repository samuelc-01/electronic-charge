# ⚡ electronic-charge

A **programmable electronic load** project using Arduino, with current control and variable load simulation for power supplies. Ideal for lab testing with electronic components and software simulations.

---

## 📌 Description

This project implements a microcontroller-controlled electronic load, capable of simulating current consumption in a controlled way.
The application was developed with:

- **Arduino UNO**
- **Simulation in Proteus 8.5**
- **Arduino IDE for programming in C++**

The embedded logic allows the load to be dynamically regulated according to the parameters defined in the code.

---

## 🔧 Components and Tools

- Arduino IDE (latest version)
- Proteus 8.5 Professional
- N-channel MOSFET (IRFZ44 or similar)
- Power resistor (for real load)
- Current sensor (optional)
- Test power supply

---

## 🗂️ Project Files

- `carga-eletronica-FINALIZADO_arduino.ino` → Source code in C++ (Arduino)
- `carga eletronica.pdsprj.zip` → Proteus project for simulation

---

## 🚀 How to Use

1. Open the `.ino` file in the **Arduino IDE**
2. Upload the code to an Arduino Uno
3. Connect the components according to the simulated circuit
4. Use the serial monitor or a digital input to change the load current
5. Simulate the circuit in Proteus if you want to test it before building it physically

---

## 💡 Possible Improvements

- LCD interface for current adjustment
- Control via potentiometer or encoder
- Real-time voltage and current measurement
- Temperature limit with sensor (NTC)
- ESP32 integration for web control

---

## 👨‍💻 Author

**Samuel Cristian dos Santos**
📍 Divinópolis – MG
📧 [samuelc.01dev@gmail.com](mailto:samuelc.01dev@gmail.com)
🔗 [linkedin.com/in/samuel-cristian](https://linkedin.com/in/samuel-cristian)
💻 [github.com/samuelc-01](https://github.com/samuelc-01)

---

## 📝 License

This project is licensed under the terms of the MIT license.
See the [LICENSE](LICENSE) file for more details.
