# control-valume-and-brightness-using-gesture
This project aims to control the system volume and screen brightness using hand gestures. 
Use your hand for volume control or brightness control. 
For detection of hand landmarks, mediapipe library is used.

# how to use this program...
step 1 :
First download the file

step 2 :
pip install -r requirements.txt or python -m pip intall -r requirements.txt

step 3:
run the python file :
	python control_volume_&_brightness.py

step 4:
select the option:
	1. volume
	2. Brightness

step 5:
then Press ctrl+c to stop the action

# Explanation..
The code uses mediapipe library to detect hand landmark positions and handedness. 
If the frame detects one hand, 
it finds out hand and triggers the brightness contreol and volume control function respectively.

// happy coding...
