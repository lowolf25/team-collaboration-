# Black Panthers Group
## Home Security System
This project will be used for Software Engineering course Assignment.

Member 1: Ali Madani
Member 2: Esmail Mubarak 

### Problem Statement 

Home security is a vital concern for every homeowner. With the advancement of technology, there are now several ways to secure your home and keep it safe from intruders. One of the most effective ways to secure your home is by using Internet of Things (IoT) devices. In this proposal, we will be discussing the use of an infrared sensor and a Raspberry Pi to create a home security system that detects any abnormal activity when the system is set to "no one at home."

### System Architecture
 
- Sensor: IR sensor
- Cloud Platform: Django
- Dashboard: Grafana 

![Flowchart](https://user-images.githubusercontent.com/117158036/214210716-55fcaa21-d0f9-484f-9eb5-34d029d42ec2.jpg)


### IOT devices 

- Rasberry Pi
- IR Sensor 


### Cloud Platform 

- The HTTPS protocol will be used in order to transmit all of the data from the sensor to the Django Rest Framework.

### Dashboard 
Dashboard for Home Security System will include the following:

1. Graph of IR Sensor Values vs Time:

  - A line graph that shows the IR sensor values over time.
  - The x-axis represents time in hours, and the y-axis represents the IR sensor values.
  - The line graph will be updated in real-time as the IR sensor values change.
  - The graph will have a legend that explains the different colors used to represent the IR sensor values.
2. List of Abnormal Activity:
  - A table that lists all abnormal activity detected by the system.
  - Each row in the table will include the following information:
    - Date and time of the abnormal activity
    - Type of abnormal activity (e.g. door opening)
    - Location of the abnormal activity (e.g. front door)
  - The table will be updated in real-time as new abnormal activity is detected.
  - The table will have a search bar that allows the homeowner to filter the list of abnormal activity by date, type, or location.
3. Control Panel:
  - A button to arm or disarm the system
  - A button to set the system to "away" mode
  - A button to set the system to "home" mode
4. System status
  - A status indicator that shows whether the system is armed, disarmed, or in away mode.
  - A message that displays the system status, such as "System armed" or "System disarmed"

![image](https://user-images.githubusercontent.com/117158036/214209080-36ab45c7-55ec-4e0d-a28b-6298fd6a8483.png)









