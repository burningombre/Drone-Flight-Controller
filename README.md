# Drone-Flight-Controller
Arduino-based quadcopter flight control system 

## Materials:
- Arduino Micro or Pro Mini
- NRF24L01+ Wireless Radios, Github library used [NRF24] (https://github.com/TMRh20/RF24)
- MPU-6050 Gyro/Accelerometer, [Arduino page] (http://playground.arduino.cc/Main/MPU-6050)
- TTL Serial Camera, [Adafruit page] (https://learn.adafruit.com/ttl-serial-camera)
- Specific quadcopter frame/ESCs/motors/props **to be decided**
 
## Checklist:
- [x] Setup Ardiono & Raspberry pi
- [x] Establish comm using the NRF24 radios + code
- [ ] Install xboxdrv + setup controller output into data packet to send
- [ ] Connect and code output for the gyro/accel to the arduino
- [ ] Use output for tweaked PID and auto-leveling functionality
- [ ] Add TTL camera to SPI, setup video data to be sent as part of a data packet
- [ ] Decide on final quad frame/ESCs/motors/props to begin construction
- [ ] Finish wiring scematic

## Wiring Diagram:
