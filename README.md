# Opencv_Gauge_Python_Mqtt
OpenCV Encoding for Analog Gauges an Casting Data Over MQTT 

Used For Liquid Gas Tank Meter Type SRG 705

requriemnts for the Python file 

 cv2 // Latest Version 
 numpy // Latest Version 
 paho.mqtt.client // Version 1.5.1

install all Pakets with Pip and Pip3
use latest Version of Pytho 3 


Settings in Analog_Gauges_reader.py
if you use allways the same image change the lines 

#get user input on min, max, values, and units
	print ("For image file:" + filename + "-calibration.jpg")
	min_angle = input('Min angle (lowest possible angle of dial) - in degrees: ') #the lowest possible angle
	max_angle = input('Max angle (highest possible angle) - in degrees: ') #highest possible angle
	min_value = input('Min value: ') #usually zero
	max_value = input('Max value: ') #maximum reading of the gauge
	units = input('Enter units: ')

    #for testing purposes: hardcode and comment out raw_inputs above
    # min_angle = 45
    # max_angle = 320
    # min_value = 0
    # max_value = 200
    # units = "PSI"

