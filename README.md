# Smart EV Accident Detection & Emergency Alert System

An Arduino-based mini project designed to enhance vehicle safety through accident detection, emergency alerts, and driver monitoring features. This project combines sensors and communication modules to create a compact and effective safety system for electric vehicles (EVs).

---

## 🚀 Features

- **Real-time Accident Detection**: Uses a tilt sensor to detect collision or rollover. Triggers automatic SMS alerts with GPS location.
- **Emergency Ventilation**: Activates a DC motor to simulate automatic window opening post-accident.
- **Alcohol Detection**: Checks driver sobriety using a digital sensor. Sends alert if alcohol is detected.
- **Temperature Monitoring**: Activates a cooling fan when the internal temperature exceeds 40°C.
- **Battery Health Monitoring**: Displays real-time battery percentage using voltage and current sensors.

---

## 🧰 Components Used

### Hardware:
- Arduino UNO
- Tilt Sensor (Digital)
- DHT11 Temperature Sensor
- Alcohol Sensor (Digital)
- GSM Module (SIM800L)
- GPS Module
- LCD Display (16x2)
- Relay Module
- DC Motor (for window simulation)
- Cooling Fan (12V)
- Voltage Sensor
- 5A ACS712 Current Sensor
- 12V Lead-Acid Battery
- Wires, Breadboard, Connectors

### Software:
- Arduino IDE

---

## 📊 System Workflow

1. **Startup**: System initializes and displays status on the LCD.
2. **Accident Detection**: Tilt sensor triggers GPS and GSM modules to send alert with location.
3. **Post-Accident Response**: Relay activates motor for 5 seconds to simulate window opening.
4. **Alcohol Check**: If alcohol is detected, alert is sent via SMS and shown on LCD.
5. **Temperature Monitoring**: Fan turns on if temperature > 40°C.
6. **Battery Monitoring**: Voltage is mapped to percentage and displayed on LCD.

---

## 📦 Installation & Wiring

1. Connect all sensors and modules to the Arduino as per your circuit design.
2. Upload the Arduino sketch via Arduino IDE.
3. Power the system using a 12V lead-acid battery.
4. Ensure GSM module has a working SIM with SMS capability.

---

## 📸 Demo & Results
- Accident detection and SMS alert successfully tested.
- Alcohol detection works with immediate SMS notification.
- Fan activates at high temperature.
- Battery level updates in real-time.

---

## 📚 References
- [IConSCEPT 2024 Paper](https://doi.org/10.1109/IConSCEPT61884.2024.10627771)
- [IJMRT Research](https://doi.org/10.5281/zenodo.11176321)
- [IJACSA Journal](http://www.ijacsa.thesai.org)

---

> Developed by: SRIJA M, YOGESH S, JATHIN P  
> Guide: Dr. SRIRANJANI R, SR. Assistant Professor, SEEE

