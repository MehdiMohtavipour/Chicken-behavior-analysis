# Chicken-behavior-analysis
Winner of Scientific-Industrial Competition of ICCKE International Conference, 2022   
The goal of this competition was to propose a machine-learning framework for chicken behavior analysis and the framework must comprise the following parts:   
1- Chicken detection in a crowded challenging poultry environment   
2- Tracker to find the trajectory of detected chickens   
3- Chicken behavior analysis based on the trajectory evaluation  
Team Name: DeepSense
Team Members: Mehdi Mohtavipour, Tahereh Zarrat Ehsan
# How to run
For chicken detection, train the YOLOv4 network using the dataset provided in the 'img' and 'Annotation' folders, formatted in YOLO style.
If you'd like to use your own dataset, employ annotation software like 'LabelImg' to create annotations and place them in these folders.
In the 'Broiler_Detection.ipynb' file, you can train the YOLOv4 network with your dataset and test it on new data.
Remember to adjust the directories according to your machine's environment. Save the trained model in the 'final_training' folder.
In the 'Broiler_Tracking.ipynb' file, the saved model is used to track chickens through centroid computations, assigning a unique ID to each chicken. The tracked video is generated by accumulating the frames.     

## Chicken Detection 
<img src="https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/d9f270e2-97fd-47fb-bbdc-76ba683e1d2e" width="450" height="450"> 

## Chicken Tracking
![Tracking_Result_1](https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/cb697e44-845e-4d06-ae04-c249e4d5e5aa)

## Chicken Activity Measurement (in terms of Pixel)
![Tracker_Distance_Mehasure_3](https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/a3a9ea6c-2225-4808-abc4-0cf5a237d9c8)

## Chicken Grouping Anomaly (Low-Temperature Paultry)
<img src="https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/31fb50aa-20e5-44ae-b654-fcab9fb3ef1f" width="450" height="450">

## Inactive Chicken Detection
<img src="https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/badc1016-8a37-4870-9eae-88bcb9f358cd" width="450" height="450">

## Certificate
<img src="https://github.com/MehdiMohtavipour/Chicken-behavior-analysis/assets/152822867/c9251d1d-6b98-4e75-96a1-50993af03e54" width="600" height="900">
