# Autonomous Lane Keep Assist and Adaptive Cruise Control for a scaled RC car
Updates and results of the Autonomous lane keep and cruise control project as part of the Automotive Electronics Integration course at CUICAR

## My contributions:
1. Development of signal processing algorithm using C code on Arduino, for one ultrasonic sensor and upgrading it to multiple sensor fusion.
2. Performed sensor sampling and selection by variance estimation techniques and implemented a Kalman filter to attenuate the noise.
3. Utilized MATLAB's curve-fitting algorithm to generate a calibration function to correlate the distance measured to the time taken for the measurement.
4. Integrating the ultrasonic sensors into a scaled 1/10th RC car and implementing 2 PID controllers for autonomous lane keep and adaptive cruise control applications.

## Challenges faced:
After a particular number of iterations, it was noticed that the car was not turning in properly, but instead turned into the corner. We then tested this using two cardboard boxes and found that when the cardboard was angled and brought near the sensor as shown in the figure below, instead of the distance value decreasing, the value instead increased. This was corrected, by implementing a code that removed any erroneous value and took the previous distance values.

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/f50e6862-0b0e-4851-9d77-cd5b49f5b6fd)

## Results:
### Sensor calibration:

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/7512324a-29e4-4ede-9963-9940497365e1)

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/afe74a3c-006e-4aa4-8b18-b518644dc473)


### Control logic algorithm:

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/c517e902-b84a-4629-814c-e5fec8b96d61)

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/22d878a8-7091-408f-a658-cc532697bbb5)


### Sensor and hardware setup:

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/e4c92b7a-d96f-482c-960e-0592edf9806e)

![image](https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/5616ee3d-aed7-4aef-b3d1-e75c12372c1f)


## Final run:

https://github.com/roh20ravikumar/Autonomous-Lane-keep-and-Cruise-control-/assets/95481658/500a687a-34f4-4065-9de5-4f02f2f08537





