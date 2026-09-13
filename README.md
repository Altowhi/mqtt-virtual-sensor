

mqtt_virtual_sensor_README.md
mqtt_virtual_sens
or_README
.md
41 lines
MD

Type / for skills




mqtt_virtual_sensor_README.md
1.84 KB •41 lines
•
Formatting may be inconsistent from source

# MQTT Virtual Sensor

A simplified MQTT virtual sensor system with a web interface, built as a collaborative project during my studies.

> 🤝 **Team project** — built together with [@mohgeis](https://github.com/mohgeis). My focus was on the theory, design, and concept side of the project; the implementation/coding was led by my teammate. See "My Contribution" below for specifics.

## 📖 What it does
The system simulates a virtual sensor that publishes data using the MQTT protocol, with a web-based interface to view sensor activity. A live version was deployed on Heroku.

## 🧰 Tech used
- **Backend:** Node.js
- **Protocol:** MQTT
- **Deployment:** Heroku

## 🙋 My Contribution
- Researched how MQTT works as a publish/subscribe protocol and why it fits IoT/sensor use cases
- Designed the system architecture — how the virtual sensor, MQTT broker, and web interface connect and exchange data
- Wrote the project report and documentation
- Presented the project for the course
- Collaborated with [@mohgeis](https://github.com/mohgeis), who implemented the code (`app.js`, `lib.js`, `sensorEntity.js`, etc.)

## ⚙️ How it works
1. A virtual sensor publishes simulated data to an MQTT broker
2. The Node.js backend subscribes to that data
3. A web interface displays the live sensor activity

## ▶️ How to run it
```bash
git clone https://github.com/Altowhi/mqtt-virtual-sensor.git
cd mqtt-virtual-sensor
npm install
npm start
```
Then open `localhost:5000` in your browser.

## 💡 What I learned
Working on the theory side gave me a solid understanding of MQTT and publish/subscribe architecture, and collaborating on a shared codebase taught me how to divide responsibilities between design/theory and implementation on a technical team.

---
*Team project — done during my studies. Original implementation by [@mohgeis](https://github.com/mohgeis).*
