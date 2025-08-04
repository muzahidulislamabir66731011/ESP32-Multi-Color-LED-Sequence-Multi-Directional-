# 🌈 ESP32 Multi-Color LED Sequence – Multi-Directional Pattern

A fun and colorful LED sequence project using an ESP32 board. This sketch lights up 5 LEDs in a multi-directional pattern—gradually turning on and off each LED to simulate a flow in both directions.

---

## 🔌 GPIO Pin Mapping

| LED Color | GPIO Pin | ESP32 Label | Resistor | Notes                       |
|-----------|----------|-------------|----------|-----------------------------|
| Red       | GPIO 2   | G2          | 220Ω     | Anode (+) to GPIO pin       |
| Yellow    | GPIO 4   | G4          | 220Ω     |                             |
| Green     | GPIO 5   | G5          | 220Ω     |                             |
| Blue      | GPIO 15  | G15         | 220Ω     |                             |
| White     | GPIO 18  | G18         | 220Ω     | Can be used for blinking    |

---

## 🛠️ Setup Instructions

1. Place 5 LEDs on a breadboard.
2. Connect each **anode (+)** of the LEDs to the ESP32 GPIO pins through **220Ω resistors**.
3. Connect all **cathodes (–)** of the LEDs to the **GND rail** on the breadboard.
4. Connect the **GND rail** to a **GND pin** on the ESP32.
5. Upload the `ESP32_Multi-Color_LED_Sequence_multi_directional.ino` sketch using Arduino IDE or PlatformIO.
6. Power the ESP32 and enjoy the LED pattern flowing in both directions!

---

## 🎯 Features

- Multi-step LED lighting effect
- Directional sequence (forward and reverse)
- Great for beginners in embedded systems
- Simple GPIO + digitalWrite control
- Customizable delay timing


---

## 📃 License

MIT License — free to use, modify, and share for personal or commercial projects.

---

