#Quadcopter stm32

Code written using HALL and STMCube.

It is a base for quadrocopter. Missing funcionality: some pid controller. 

Funcionalities: 
+ Reciveing and handling control signal send via UART
+ Sending back via UART information from IMU (pitch, roll, yaw) 
+ Generating PWM signal based on received control singnal and distribute it to four motor drvers
