# Paper Robot - Base

![Example of paper robot base](paper_robot_base.jpg)

## Papercraft

The average building time for cutting, bending and glueing will take about 25min.

ð [Paper Bot - Base v2.pdf](papercraft/Paper%20Bot%20-%20Base%20v2.pdf)

## Testing

The base is ideal for testing your components and your program before moving to the final assembly.

You could easily place the breadboard, ultrasonic sensor and the servos together with the Calliope Mini Board for testing.

![Example of paper robot base for testing](images/paper_robot_base_assembled.jpg)

## Connection Pins

The following pins are used for the different kind of sensors and actors.

| Name                     | Device Pin | Calliope Mini Pin | Battery Pack |
| ------------------------ | ---------- | ----------------- | ------------ |
| Micro Servo SG90 (left)  | GND â      | -                 | GND â        |
| Micro Servo SG90 (left)  | SIGNAL ð¦¾  | P1 /C1 ð          | -            |
| Micro Servo SG90 (left)  | VCC â¡     | -                 | 5V â¡        |
| Micro Servo SG90 (right) | GND â      | -                 | GND â        |
| Micro Servo SG90 (right) | SIGNAL ð¦¾  | P2 /C2 ð          | -            |
| Micro Servo SG90 (right) | VCCâ¡      | -                 | 5V â¡        |
| Ultrasonic HC SR04       | GND â      | -                 | GND â        |
| Ultrasonic HC SR04       | TRIG ðª     | P0 /C0 ð¡         | -            |
| Ultrasonic HC SR04       | ECHO ð¤    | P3 /C3 ð¢         | -            |
| Ultrasonic HC SR04       | VCC â¡     | -                 | 5V â¡        |

## Wiring

For wiring the different kind of connection, the following is recommend.

### Micro Servos SG90 wiring

Example wiring for the micro servo SG90 with contact pins or pin headers.

#### Micro Servos SG90 wiring with contact pins

![Example of servo wiring](../fritzing/servo_wiring.png)

#### Micro Servos SG90 wiring with pin header

![Example of servo wiring with pin header](../fritzing/servo_wiring_pin_header.png)

### Ultra Sonic HC-SRC04 wiring

Example wiring for the ultra sonic HC-SRC04 sensor with contact pins or pin headers.

#### Ultra Sonic HC-SRC04 wiring with contact pins

![Example of ultra sonic wiring](../fritzing/ultrasonic_wiring.png)

#### Ultra Sonic HC-SRC04 wiring with pin header

![Example of ultra sonic wiring](../fritzing/ultrasonic_wiring_pin_header.png)

### Micro Servos SG90 and Ultra Sonic HC-SRC04 wiring

Example wiring for the micro servo SG90 and ultra sonic HC-SRC04 sensor with contact pins or pin headers.

#### Micro Servos SG90 and Ultra Sonic HC-SRC04 wiring with contact pins

![Example of servo and ultra sonic wiring](../fritzing/servo_and_ultrasonic_wiring.png)

#### Micro Servos SG90 and Ultra Sonic HC-SRC04 wiring with pin header

![Example of servo and ultra sonic wiring](../fritzing/servo_and_ultrasonic_wiring_pin_header.png)

## Example Program / Test Program

### Configuration

For the example program we are using the following robot configuration.

![Example test configuration](images/example_test_configuration.png)

### Program

The following program could be used for a simple test to see if everything works correct.

![Example test program](images/example_test_program.png)
