[//]: # (Image References)

[image1]: ./images/key_pts_example.png "Facial Keypoint Detection"

# Facial Keypoint Detection

## Project Overview

In this project, knowledge of computer vision techniques and deep learning architectures are used to build a facial keypoint detection system. 
Facial keypoints include points around the eyes, nose, and mouth on a face and are used in many applications. 
These applications include: facial tracking, facial pose recognition, facial filters, and emotion recognition. 

![Facial Keypoint Detection][image1]

The project is broken in two notebooks.


__Notebook 2__ : Defining and Training a Convolutional Neural Network (CNN) to Predict Facial Keypoints

__Notebook 3__ : Facial Keypoint Detection Using Haar Cascades and the Trained CNN

Here is an example of how final system works. The following earlier unseen photo is provided during the test

![ScreenShot](/screenshots/obamastest.png)



The haarcascade detects boxes around faces on the photograph
![ScreenShot](/screenshots/haarcascadeobamas.png)

Then each of the detected faces is fed through keypoint detection model trained in notebook 2 with the following results
![ScreenShot](/screenshots/barackkeypoints.png)
![ScreenShot](/screenshots/michellkeypoints.png)
