# STM32F4-SELFPARKING_CAR

Theory

This project can be described as an extremely simple project as the equipment it contains. Distance sensors connected to the microprocessor send the data to the processor in real time. If sufficient range is detected, the robot is parked with dc motors connected to the motor drive card.

Sceneraio

•After 5 seconds of wake-up call, the robot starts to move straight ahead.

•It continuously receives data from 2 ultrasonic sensors when running.

•When  2  ultrasonic  sensors  measure  more  than  a  certain  value,  the  parking  state  is decided.

•Parallel parking is provided with back and forwardmaneuvers.

