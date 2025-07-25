# 🔐 IoT-Based Women Security Watch

This is an **IoT-enabled wearable device** designed to enhance women's safety through **real-time location tracking and emergency alert messaging**. The device is built using **Arduino UNO**, **GPS**, and **GSM** modules, and is implemented as a **wristwatch** for easy access during emergency situations.

---

## 📌 Project Overview

The goal of this project is to provide a **compact, portable, and affordable safety device** for women that can:
- Send an **SOS alert** via SMS
- Include **live GPS coordinates** in the message
- Function through a **simple panic button interface**

---

## 🛠️ Technologies & Components Used

- **Arduino UNO**
- **GSM Module (SIM800L or SIM900)**
- **GPS Module (NEO-6M)**
- **Push Button / Vibration Sensor**
- **Rechargeable Battery (9V or Li-ion)**
- **Voltage Regulator Module (LM317/LM2596)**
- **Arduino IDE (C/C++)**

---

## 🧠 How It Works

1. The user presses the **emergency button**.
2. The **GSM module** sends a **text message** to predefined emergency contacts.
3. The **GPS module** provides the **current location** which is embedded in the message.
4. Contacts receive a message like:  
   `"Emergency! I need help. My location: https://maps.google.com/?q=latitude,longitude"`

---

## 🧾 Features

- ✅ Real-time **location tracking**
- ✅ **SOS alert** via SMS
- ✅ Compact, **wearable wristwatch design**
- ✅ Low power consumption
- ✅ Easy to use during emergencies

---

## 📂 Project Structure

📁 IoT-Women-Security-Watch/
│
├── Code/
│ └── women_safety_watch.ino
│
├── Circuit/
│ └── circuit_diagram.jpg
│
├── Docs/
│ ├── Project_Report.pdf
│ └── Presentation.pptx
│
├── Images/
│ └── watch_prototype.jpg
│
└── README.md

---

## 📸 Screenshots

*(Add images to the `/Images` folder and link them here)*

---

## 🚀 Future Improvements

- Integrate **voice recognition** or **fall detection**
- Connect with **mobile apps** via Bluetooth
- Add **vibration motor** for haptic feedback
- Enable **live tracking via cloud**

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [GitHub Issues](https://github.com/yourusername/IoT-Women-Security-Watch/issues).

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
