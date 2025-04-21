🚗 Vehicle Detection and Indication System
A real-time, Arduino-based system designed to detect the presence of a vehicle using an ultrasonic sensor and alert via LED indication.

🛠️ Components Used
Arduino Uno

Ultrasonic Sensor (HC-SR04)

LED

Resistor (220Ω)

Jumper Wires

Breadboard or PCB

Power Supply

⚙️ How It Works
The ultrasonic sensor continuously measures the distance in front.

When a vehicle (or object) comes within a threshold (e.g., 50 cm), the LED turns ON.

The system resets once the object moves away.

💡 Applications
Smart parking systems

Vehicle counting at tolls

Safety systems in restricted zones

📐 Circuit Connections
HC-SR04 Trigger → Pin 9

HC-SR04 Echo → Pin 10

LED → Pin 7 (with a 220Ω resistor)

VCC/GND to Arduino 5V/GND

🧠 Future Enhancements
Use a buzzer for sound alerts

Display count or distance on an LCD

Integrate with IoT for real-time monitoring

