# Smart Grocery Shopping Trolley 🛒

This project is a prototype of a **Smart Grocery Shopping Trolley** designed to improve the shopping experience by automating item scanning, billing, and total cost calculation using embedded electronics.

---

## 🔧 Project Description

The Smart Trolley eliminates long queues and manual billing by automating the process. It uses:

- **PIC Microcontroller** (e.g., PIC16F877A)
- **LCD Display** (16x2)
- **IR Sensors or RFID** for item detection
- **Power Supply** (not battery-operated)

When a product is placed in the trolley, the sensor detects it, fetches the product code, and the microcontroller updates the total cost. The LCD shows the product name, price, and running total.

---

## 📦 Features

- Automatic item detection using sensors
- Live bill update on LCD screen
- Removes need for billing counter queues
- Simple embedded C code for PIC microcontroller

---

## 🔌 Hardware Requirements

- PIC16F877A Microcontroller
- 16x2 LCD
- IR Sensor / RFID Reader
- Power Supply (Center-tapped Transformer based)
- Resistors, Capacitors, Crystal Oscillator

---

## 💻 Software Requirements

- MPLAB IDE or MikroC for PIC
- Proteus (for simulation)
- Git & GitHub
- Any code editor (VS Code / Notepad++)

---

## 🔁 How It Works

1. Product is scanned via IR or RFID.
2. The microcontroller reads product code.
3. Price is fetched and added to running total.
4. LCD displays product info and total bill.

---

## 🧠 Future Improvements

- GSM Module for SMS-based billing
- Mobile app integration for cart summary
- Weight sensor for accuracy
- IoT-based real-time cart monitoring

---

## 📁 Project Structure

```bash
smart-grocery-shopping-trolley/
│
├── code/                  # Embedded C code for PIC
├── circuit/               # Circuit diagram images
├── simulation/            # Proteus files (optional)
├── images/                # Photos or screenshots
├── docs/                  # Project report, block diagram, etc.
└── README.md              # Project overview
