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
1.	System should continue working during temporary communication interruptions.
2.	Command processing should normally finish within 5 seconds.
3.	System should support multiple rovers at the same time.
4.	Only authenticated operators should be allowed to send commands. 
