# wireless_noticeboard_display_using_bluetooth
A Wireless Noticeboard Display using Bluetooth is a system that allows users to send and update messages remotely on an electronic noticeboard via Bluetooth. It is commonly used in schools, offices, and public places to display announcements dynamically without manual intervention.

Key Features:
Wireless Communication: Uses Bluetooth (HC-05 or HC-06 module) to receive messages from a mobile phone or computer.
Electronic Display: Can use LCD (16x2, 20x4), LED Matrix, or an OLED screen for message display.
Microcontroller-Based System: Controlled using Arduino, ESP32, or Raspberry Pi to process and display messages.
Mobile App or PC Interface: Messages can be sent via a custom-built Android app, terminal software, or Bluetooth serial communication.
Low Power & Cost-Effective: Runs on battery or low-power supply, making it suitable for various environments.


Components Required:
Microcontroller: Arduino Uno/Nano, ESP32, or Raspberry Pi
Bluetooth Module: HC-05 / HC-06
Display Unit: 16x2 LCD, LED Matrix, or OLED
Power Supply: 5V adapter or battery
Software: Arduino IDE for coding, MIT App Inventor for mobile app development


Working Principle:
A user sends a message via a Bluetooth-enabled mobile app or computer.
The Bluetooth module (HC-05/HC-06) receives the message and sends it to the microcontroller.
The microcontroller processes the data and updates the electronic display.
The displayed message can be updated or cleared remotely.
