# Rocket1-sensors
This is the very first stage and does not have too much of functionality 

To run 
Steps to follow: 
```bash
cd /Rocket1-sensors
python MPL3115A2.py
```
### Sensors used 
MPL3115A2 - Altimeter, pressure ,temperature
<br>
Servo - Any (SG 900 used in my case) 

### Purpose for the code 
The follwing code gets the current altitude , pressure , tempearture every second and stores them in txt file in JSON format and 
records the highest altitude(In my case for the rocket). If there is a diffrence from the highest and the current altitude of 
1 meter then it turns the servo to 180 degrees(In our case this is used for the parachute deployment).
