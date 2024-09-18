# SCADA
Capstone - SCADA (Supervisory Control and Data Acquisition)

This is the Capstone (SCADA) project I worked on with my group during my time at Toronto Metropolitan University.
This project was to create a SCADA system that allows a user to view the graphs and data through a GUI (Graphical User Interface), and control loads through relay system, or rather a PLC (Progammable Logic Controller).
We were able to accomplish this through the Arduino Opta PLC, a Diris A10 Power Meter, and 3 current transformers.
The PLC allowed us the use of 4 relays to simulate a real life PLC control in combination with the Power meter and current transformers allows the system to read voltages, currents, frequencies, real power, reactive pwoer, and apparent power.
With these, we used MODBUS RTU protocol to get the readings from the registers of the power meter, and the control the PLC through the serial port for the Arduino Opta PLC.
We used python to develop the GUI which displays all the expected graphs for users to view, and the Arduino cloud to control the PLC through the serial port, we were able to accomplish this through the Arduino Cloud which allows us to also control the PLC through our phones.

<!--
<img src="https://github.com/user-attachments/assets/bc800d42-9adb-4809-be05-e38c3c93ba8e" alt="Project 2" style="width:30%; height:auto;">
![Exe](https://github.com/user-attachments/assets/ea9aeb7f-4474-4b29-997a-4b38978fec78)
![Graph1](https://github.com/user-attachments/assets/74f496af-dfbd-4eb7-b15e-4ab45730e7a9)
![Graph2](https://github.com/user-attachments/assets/93922a86-f347-48d4-95dc-4d3d5ebc56ee)
![GUI](https://github.com/user-attachments/assets/032f024f-e5c1-4f46-bba5-285126f2a743)
![Login](https://github.com/user-attachments/assets/53d09a3a-e233-427b-bf14-ba6dde5eb840)
![History](https://github.com/user-attachments/assets/db0e437d-4ef1-4f52-9102-82e89f13f2cc)
![PXL_20240426_180533252](https://github.com/user-attachments/assets/9a4d1eb9-3c56-4f7f-8a8d-bedd490febdd)
![Arduino](https://github.com/user-attachments/assets/2956f85c-f7a5-4ad1-a34c-cd06edd00425)

[![Watch the video](https://img.youtube.com/vi/9twqcwSKyeY/0.jpg)](https://www.youtube.com/watch?v=9twqcwSKyeY)
https://youtu.be/VzXaLzevTk8
-->
## The Executionable we created through Python
<img src="https://github.com/user-attachments/assets/ea9aeb7f-4474-4b29-997a-4b38978fec78" alt="Project 2" style="width:10%; height:auto;">

## The Login we created for user to input username and password
<img src="https://github.com/user-attachments/assets/53d09a3a-e233-427b-bf14-ba6dde5eb840" alt="Project 2" style="width:20%; height:auto;">

## The GUI (Graphical User Interface)
<img src="https://github.com/user-attachments/assets/032f024f-e5c1-4f46-bba5-285126f2a743" alt="Project 2" style="width:80%; height:auto;">

## The GUI Graphs of the loads activating
<img src="https://github.com/user-attachments/assets/74f496af-dfbd-4eb7-b15e-4ab45730e7a9" alt="Project 2" style="width:80%; height:auto;">

## The GUI of the system when current overload occurs
<img src="https://github.com/user-attachments/assets/93922a86-f347-48d4-95dc-4d3d5ebc56ee" alt="Project 2" style="width:80%; height:auto;">

## Example of the graphs being displayed through Arduino Cloud Dashboard
<img src="https://github.com/user-attachments/assets/2956f85c-f7a5-4ad1-a34c-cd06edd00425" alt="Project 2" style="width:80%; height:auto;">

## Example of the Arduino Cloud Data History for future evaluation
<img src="https://github.com/user-attachments/assets/db0e437d-4ef1-4f52-9102-82e89f13f2cc" alt="Project 2" style="width:50%; height:auto;">

## The complete build of the SCADA hardware system built for this project
<img src="https://github.com/user-attachments/assets/9a4d1eb9-3c56-4f7f-8a8d-bedd490febdd" alt="Project 2" style="width:80%; height:auto;">

## This is the video submission of our finsihed project.
[![Watch the video](https://img.youtube.com/vi/VzXaLzevTk8/0.jpg)](https://www.youtube.com/watch?v=VzXaLzevTk8)
