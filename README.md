# HAND-GESTURE-CONTROLLED-MOTOR-CAR

## AIM
TO CONTROL RC MOTOR CAR WITH HAND MOVEMENTS - ESP32 NOW APPLICATION


## COMPONENTS

- ESP32 x2
- DC motor x4
- L293D motor driver
- 12V adapter
- Accelerometer
- Jumper Wire
- USB cable

## CONNECTION

### Accelerometer Pin Diagram

![Accelerometer](https://github.com/user-attachments/assets/403b364a-441e-4159-8c13-4392bf09204e)

 - VCC = power supply ---->  3V3
 - X-out = X Axis analog output  ---->  GPIO36
 - Y-out = Y Axis analog output  ---->  GPIO39
 - Z-out = Z Axis analog output  ---->  GPIO34
 - GND = ground          ---->  GND

### L293D Motor Driver Module

![L293 MOTOR DRIVER MODULE](https://github.com/user-attachments/assets/eecb9d39-1c1c-4afa-b242-36d290c868eb)

<br> on left side:
- A1 = Input Pin 1   ---->  GPIO5
- A2 = Input Pin 2   ---->  GPIO32
- B1 = Input Pin 3   ---->  GPIO33
- B2 = Input Pin 4   ---->  GPIO25
  
<br> on right side
- MA 1 = Output Pin 1   ----> +ve DC Motor 1
- MA 2 = Output Pin 2   ----> -ve DC Motor 1
- MB 1 = Output Pin 3   ----> +ve DC Motor 2
- MB 2 = Output Pin 4   ----> +ve DC Motor 2
- +V = 5V supply ----> +ve terminal of ESP32 development board
- -V = GND ---->  -ve terminal of ESP32 development board

##### ESP32 Development Board
![WhatsApp Image 2025-02-25 at 11 10 12 AM](https://github.com/user-attachments/assets/a7ae9056-3012-4873-9db9-3e5a6d0471bc)



  
  
