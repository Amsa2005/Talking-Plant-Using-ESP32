# 🌱 Talking Plant Using ESP32

A smart IoT-based system that gives your plant a “voice” by monitoring environmental conditions and playing real-time voice alerts through a speaker.

## 📌 Project Overview

This project uses an ESP32 microcontroller along with various sensors (soil moisture, temperature, humidity, and light) to monitor a plant's health. When a threshold is crossed, the system plays a relevant pre-recorded MP3 message using the DFPlayer Mini, making plant care more interactive and educational.

## 🎯 Objective

To create an interactive plant care assistant that uses real-time sensor inputs and audio messages to notify users about plant needs like water or sunlight.

## 🧩 Components Used

| Component          | Quantity | Purpose                             |
|--------------------|----------|-------------------------------------|
| ESP32 Dev Board     | 1        | Main controller                     |
| DFPlayer Mini       | 1        | Plays MP3 voice messages            |
| DHT22 Sensor        | 1        | Measures temperature & humidity     |
| Soil Moisture Sensor| 1        | Detects soil dryness                |
| LDR                 | 1        | Detects light intensity             |
| PAM8403 Amplifier   | 1        | Boosts audio output                 |
| Speaker             | 1        | Plays audio alerts                  |
| microSD Card        | 1        | Stores MP3 audio files              |
| Breadboard & Wires  | As needed| Circuit connections                 |
| Power Supply        | 1        | Powers the ESP32 board              |

## ⚙️ Working Principle

- Sensors send environmental data to the ESP32.
- Based on the readings, the ESP32 triggers the DFPlayer Mini to play relevant voice clips.
- These clips alert users with messages like **"Water me!"** or **"I need sunlight!"**

## 🛠️ How to Build

1. Connect all sensors and DFPlayer to the ESP32 on a breadboard.
2. Store voice messages as `.mp3` files on a microSD card.
3. Upload the Arduino sketch to the ESP32.
4. Power the device and test the sensor-triggered audio alerts.

## ✅ Results

- Accurately detects soil, temperature, humidity, and light levels.
- Plays the correct voice messages when thresholds are met.
- Engaging and fun way to learn IoT and embedded systems.

## ⭐ Features

- No display required (cost-efficient)
- Interactive and beginner-friendly
- Great educational project for IoT learning

## 🚫 Limitations

- No remote or mobile monitoring
- Requires pre-recorded MP3 messages
- Best suited for controlled environments

## 🚀 Future Enhancements

- Add Wi-Fi to send data to a mobile app
- Include a water pump for auto-watering
- Add multilingual or custom voice responses
- Enable solar-powered or battery operation

## 👩‍💻 Team Members

- Amsa S  
- Mohana A  
- Suganthi M  
- Sowmiya S  
- Arundhathi I  
- Lavanya T  
- Lathika Saran S  
- Zeenath Usaima M A S  
- Supriya D  

## 🏫 Institution

**Madras Institute of Technology**  
Department of Computer Technology  
Submitted as part of the Industry Oriented Course – IoT Mini Project (April 2025)

## 📚 References

- [Arduino Official Docs](https://www.arduino.cc/en/Guide)
- [DFPlayer Mini Datasheet](https://www.dfrobot.com/wiki/index.php/DFPlayer_Mini)
- [DHT Sensor Library](https://github.com/adafruit/DHT-sensor-library)
- [ESP32 Documentation](https://docs.espressif.com/)
- [TTSMP3.com](https://ttsmp3.com)

---

> If you found this project interesting, feel free to ⭐ star the repo!
