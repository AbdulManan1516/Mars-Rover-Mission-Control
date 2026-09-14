# Mars-Rover-Mission-Control

1. Functional Requirements (FRs)
1.	Rover shall receive and execute valid commands.
2.	Rover shall report its current location.
3.	Rover shall report battery level and temperature.
4.	Rover shall report communication status.
5.	System shall reject invalid or unauthorized commands.
6.	Rover shall enter Safe Mode during critical battery/thermal conditions.
7.	Mission Control shall receive command execution status.
8.	System shall record commands and critical events with timestamp and operator ID. 
Non-Functional Requirements (NFRs)
1.	Rover must enter Safe Mode within 3 seconds if battery temperature is too high or battery capacity is critically low. 
2.	System must support at least 20 rovers simultaneously
3.	Commands can only be accepted from operators who are authenticated and have the required role/authorization. 
4.	Only authenticated operators should be allowed to send commands. 
