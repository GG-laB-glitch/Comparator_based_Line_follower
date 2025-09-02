# Comparator_based_Line_follower
Line Follower Robot (Without Microcontroller)

This project implements a Line Follower Robot using analog electronics instead of a microcontroller. The robot follows a black line on a white surface (or vice versa) using IR sensors, LM358 comparators, and an L298N motor driver to control DC motors.

By eliminating the need for programming, the design demonstrates a cost-effective and beginner-friendly approach to building autonomous robots.

📌 Features

Follows a predefined line using IR sensors.

No microcontroller required – purely analog circuit.

Uses LM358 comparator for sensor signal processing.

Uses L298N motor driver to control two DC motors.

Simple, low-cost, and efficient design for educational robotics.

🛠️ Components Used

Transformer/DC Source (12V, 5V)

Diode (1N4007)

Comparator IC (LM358)

Resistors (220kΩ, 10kΩ, etc.)

Motor Driver Module (L298N)

IR Sensor Module (LM393)

LEDs

DC Motors

Potentiometer

⚙️ Working Principle

IR Sensors detect line color (black absorbs, white reflects).

LM358 Comparator compares sensor signals with a reference voltage.

Comparator outputs are fed to the L298N motor driver.

Based on sensor readings, the robot:

Moves forward if both sensors detect white.

Turns left/right if one sensor detects black.

Stops if both detect black.

🔌 Circuit Overview

IR sensors → LM358 comparator → L298N motor driver → DC motors

LEDs indicate sensor status.

Potentiometer allows adjusting sensor sensitivity.
