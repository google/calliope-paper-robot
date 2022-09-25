# Paper Robot - Base

![Example of paper robot base](paper_robot_base.jpg)

## Papercraft

The average building time for cutting, bending and glueing will take about 25min.

📄 [Paper Bot - Base v2.pdf](papercraft/Paper%20Bot%20-%20Base%20v2.pdf)

## Testing

The base is ideal for testing your components and your program before moving to the final assembly.

You could easily place the breadboard, ultrasonic sensor and the servos together with the Calliope Mini Board for testing.

![Example of paper robot base for testing](images/paper_robot_base_assembled.jpg)

## Connection Pins

The following pins are used for the different kind of sensors and actors.

| Name                     | Device Pin | Calliope Mini Pin | Battery Pack |
| ------------------------ | ---------- | ----------------- | ------------ |
| Micro Servo SG90 (left)  | GND ⏚      | -                 | GND ⏚        |
| Micro Servo SG90 (left)  | SIGNAL 🦾  | P1 /C1 🟠         | -            |
| Micro Servo SG90 (left)  | VCC ⚡     | -                 | 5V ⚡        |
| Micro Servo SG90 (right) | GND ⏚      | -                 | GND ⏚        |
| Micro Servo SG90 (right) | SIGNAL 🦾  | P2 /C2 🟠         | -            |
| Micro Servo SG90 (right) | VCC⚡      | -                 | 5V ⚡        |
| Ultrasonic HC SR04       | GND ⏚      | -                 | GND ⏚        |
| Ultrasonic HC SR04       | TRIG 🕪     | P0 /C0 🟡         | -            |
| Ultrasonic HC SR04       | ECHO 🎤    | P3 /C3 🟢         | -            |
| Ultrasonic HC SR04       | VCC ⚡     | -                 | 5V ⚡        |

## Wiring

For wiring the different kind of connection, the following is recommend.

### Micro Servos SG90 wiring

![Example of servo wiring](images/base_servos_wiring.png)

### Ultra Sonic HC-SRC04 wiring

![Example of ultra sonic wiring](images/base_ultrasonic_wiring.png)

### Micro Servos SG90 and Ultra Sonic HC-SRC04 wiring

![Example of servo and ultra sonic wiring](images/base_servo_and_ultrasonic_wiring.png)

## Example Program / Test Program

### Configuration

For the example program we are using the following robot configuration.

![Example test configuration](images/example_test_configuration.png)

### Program

The following program could be used for a simple test to see if everything works correct.

![Example test program](images/example_test_program.png)
