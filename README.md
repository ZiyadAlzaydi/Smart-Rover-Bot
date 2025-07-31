# Smart-Rover-Bot
The Smart Rover Bot is an autonomous obstacle-avoiding robot built using Arduino. It uses an ultrasonic sensor mounted on a servo motor to scan its environment and detect obstacles in multiple directions.
The robot moves forward until it senses an obstacle, then intelligently scans left and right to choose the clearest path and avoid collisions.

Powered by a L298N motor driver, it controls four DC motors for smooth forward and turning motion. This makes it a great project for learning about robotics, sensors, and autonomous navigation.

![image](https://github.com/user-attachments/assets/d0c4330a-e5c1-4cb9-b620-1dfe46c17cb9)


 Hardware Components Used:
 
	1.	L298N Motor Driver Module
	•	Controls 4 DC motors (2 pairs of wheels).
	2.	Ultrasonic Sensor (HC-SR04)
	•	Detects obstacles ahead.
	3.	Servo Motor
	•	Rotates the ultrasonic sensor to scan left and right.
	4.	Arduino Board
	•	Acts as the main controller.
	5.	Chassis with 4 DC Motors and Wheels
	•	Provides movement.
	6.	Wires & Battery Pack
	•	Powers and connects components.

⸻

 How It Works:
 
	1.	The servo motor rotates the ultrasonic sensor to scan the distance in front, left, and right.
	2.	If an obstacle is detected within a set distance (e.g. 10–20 cm):
	•	The robot stops, scans left and right.
	•	It chooses the direction with more space and turns that way.
	3.	If no obstacle is found, the robot moves forward.
	4.	All 4 motors are powered by the L298N motor driver, controlled by the Arduino.

⸻

 Features:
 
	•	Basic autonomous navigation.
	•	Avoids collisions by decision-making logic.
	•	Fully Arduino-based, expandable (e.g. add line sensors, Bluetooth, etc.).
