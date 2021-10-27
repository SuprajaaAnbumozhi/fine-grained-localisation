# Fine-grained Localisation

## Overview
Geolocation is the problem of localising a person or device in the world using sensor data. 
Geolocation is an important problem in many AI and computing applications, from autonomous 
vehicle navigation to search engine queries based on the user’s current location. Here, 
we will investigate the problem of fine-grained geolocation in an art museum. Various Computer
Vision techniques are used  to recognize the location from where an image was taken.

## Requirements
	- pandas==0.22.0
	- cv2==4.4.x
	- tensorflow
    - tqdm
    - numpy
    - sklearn
    - matplotlib

**Note**: The above mentioned is the minimum version requirements needed to run this algorithm.

## Files Required to run
1. COMP90086_2021_Project_test.zip
2. COMP90086_2021_Project_train.zip
3. cnn.ipynb
4. sift.ipynb

All the above mentioned files need to be within the same folder.

## Steps to run
1. Open the cnn.ipynb. Run all
2. Open sift.ipynb. Run all

## Where to find the predictions?
1. The output of CNN will be stored in the same folder with the name cnn_predictions.csv
2. The output of SIFT+FLANN algorithm will be stored in the same folder in the name sift_predictions.csv
