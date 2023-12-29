# Standard-Pose-Estimation
**The provided code is a Python script that uses the MediaPipe library to detect and classify betwen Sitting and Standing poses in images.**

**I have used the MediaPipe Pose model with specific configurations to work in static image mode.**
**First program takes an image as input and detects the pose landmarks using the MediaPipe Pose model.**
**For Standing and Sitting Position - I calculated the knee angle and hip angle using the landmarks - "Knee, Hip ,Ankle and Shoulder joint".**
**Then depends on the angle , output image will be saved with label on it either Sitting, Standing or Unknown.**
**The output image is saved in the 'Outputs' directory with a proc_ prefix**

**There is also an Landmark Display option to see the pose landmarks on the input image.**

**This script can be used to analyze images of individuals and classify them into "Standing" or "Sitting" based on the detected joint angles. It leverages the MediaPipe Pose model for pose landmark detection and provides a visualization of the results.**
## Results
![output](https://github.com/tushaar9560/Standard-Pose-Estimation/assets/101884854/cccea264-cb0b-4c88-8d97-b21a210a4820)

![proc_standing](https://github.com/tushaar9560/Standard-Pose-Estimation/assets/101884854/5fdff223-74a4-4dca-bfc4-d0ea9ab2ecc4)
