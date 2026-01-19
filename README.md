# Student Portfolio in COSC 111

**Subject:** Internet of Things (IoT) Laboratory  
**Student Name:** [INSERT YOUR NAME HERE]  
**Section:** [INSERT YOUR SECTION HERE]  
**Instructor:** [INSERT INSTRUCTOR NAME]

---

## 📖 Portfolio Overview
This repository serves as a compilation of all laboratory activities, examinations, and prototypes developed for the **COSC 111** course. The projects range from basic digital signal processing on an Arduino to complex, bi-directional communication systems involving Python scripts and FastAPI web servers.

Each folder contains the source code (`.ino`, `.py`) and a detailed documentation file explaining the circuit logic and implementation.

---

## 📂 Laboratory Activities

### [Laboratory Activity 1: Working with Digital Signals](./Laboratory%20Activity%201)
* **Focus:** Digital Output, `digitalWrite()`
* **Description:** A foundational project implementing a "Running Light" circuit. It demonstrates the control of multiple LEDs in a sequential pattern using digital high/low signals.

### [Laboratory Activity 2: Working with Analog Signals](./Laboratory%20Activity%202)
* **Focus:** PWM (Pulse Width Modulation), `analogWrite()`
* **Description:** An evolution of the running light circuit that introduces analog signals. It controls the brightness of LEDs rather than just their on/off state, utilizing arrays and loops for efficient pin management.

### [Laboratory Activity 3: Working with Sensors](./Laboratory%20Activity%203)
* **Focus:** Analog Input, Sensors (Thermistor & Photoresistor)
* **Description:** A "Fire Sensor" prototype. This system reads real-time data from temperature and light sensors, triggering a visual alarm (flashing LED) when environmental readings exceed defined safety thresholds.

### [Laboratory Activity 4: Arduino Serial Connection](./Laboratory%20Activity%204)
* **Focus:** Serial Communication, UART
* **Description:** A remote-controlled sensor system. It sends sensor data to the Serial Monitor and allows the user to manually override alarms by typing text commands directly into the Arduino console.

### [Laboratory Activity 5: Receiving Serial Connection from Python](./Laboratory%20Activity%205)
* **Focus:** Python Integration, `pyserial`
* **Description:** A software-hardware integration project. A Python script runs on the host computer, providing a terminal-based UI that allows the user to toggle specific LEDs on the Arduino board.

### [Laboratory Activity 6: Bidirectional Control](./Laboratory%20Activity%206)
* **Focus:** Full Duplex Communication, Synchronization
* **Description:** A complex feedback loop system. Pushing physical buttons on the Arduino sends signals to Python, which processes the request and sends commands back to the Arduino to control output LEDs, simulating a responsive IoT environment.

### [Laboratory Activity 7: Controlling Arduino using FastAPI](./Laboratory%20Activity%207)
* **Focus:** Web APIs, HTTP, FastAPI
* **Description:** Replaces the terminal interface with a modern web API. The Arduino hardware is controlled via HTTP endpoints (e.g., `/led/red`), bridging the gap between hardware serial ports and web technologies.

---

## 🏆 Examinations

### [Midterm Exam: Smart Lighting System](./Midterms)
* **Project:** Environment-Aware Automatic Lighting
* **Description:** A smart system with "Manual" and "Automatic" modes. In Auto mode, it simulates weather conditions (Cloudy, Sunny) and adjusts LED indicators dynamically based on light intensity readings.

### [Final Exam: Arduino-to-Python API Client](./Finals)
* **Project:** Physical API Trigger
* **Description:** A "Physical Client" system where the Arduino acts as a tactile trigger. Pressing a button on the hardware signals a Python script to perform a real HTTP request to a remote API server, demonstrating the decoupling of hardware input from network logic.
