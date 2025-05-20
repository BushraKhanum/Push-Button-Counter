# PUSH BUTTON COUNTER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: BUSHRA KHANUM

*INTERN ID*: CT04DK44

*DOMAIN*: EMBEDDED SYSTEM

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

This project is a simple and beginner-friendly implementation of a push button counter using an Arduino UNO. The system is designed to increment a counter each time a button is pressed and display the count in real-time via the Serial Monitor. It is ideal for understanding basic digital input handling, debouncing techniques, and serial communication in embedded systems.

*Project Overview*

The main objective of this project is to detect button presses and count how many times the button has been pressed. Every time the user presses the button, the Arduino reads the input signal, increments the counter by one, and prints the updated count value on the Serial Monitor. This type of setup is often used in digital systems to monitor user inputs or events, such as in voting machines, attendance counters, and inventory management systems.

*Components Used*

Arduino UNO

Push Button

10kΩ Resistor (for pull-down configuration)

Breadboard and Jumper Wires

Serial Monitor

*Working Principle*

The push button is connected to a digital input pin on the Arduino, and a pull-down resistor ensures the input reads LOW when the button is not pressed. When the button is pressed, the pin reads HIGH, indicating an event. To ensure accurate readings, a software debounce mechanism is added to prevent multiple triggers caused by mechanical noise or bouncing.

Each valid button press causes the internal counter variable to increment by one. The updated counter value is then printed on the Serial Monitor. This provides a clear and real-time view of how many times the button has been pressed.

*Key Features*

Counts and displays the number of button presses.

Includes software debouncing for stable readings.

Real-time feedback via Serial Monitor.

Easily extendable to work with LCD or 7-segment displays.

*Code Functionality*

The code initializes the button pin as input and sets up serial communication. Inside the loop() function, it continuously checks the button state. If a valid press is detected (HIGH state with debounce delay), it increments the counter and prints the result.

*Applications*

Basic event counting (e.g., people entering a room)

Learning tool for digital input and output

Foundation for more complex user-interface projects

*Future Enhancements*

Add an LCD or OLED display to show the count without using a computer.

Use an external interrupt to improve responsiveness.

Add reset functionality with a second button.

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/04dcd2a3-8d89-40a2-9d28-755e4603d1f6)












