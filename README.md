# REAL-TIME-VISION-PROCTORING

Real time automated vision proctoring using Computer Vision and Machine Learning.

## Using MediaPipe Framework

MediaPipe ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate 3D surface via regression. It allows the network to dedicate most of its capacity towards coordinate prediction accuracy. Each landmark consists of the following: x and y: Landmark coordinates normalized to [0.0, 1.0] by the image width and height respectively. z: Distance between the camera and the user visibility: A value in [0.0, 1.0] indicating the likelihood of the landmark being visible (present and not occluded) in the image.MediaPipe ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate 3D surface via regression. It allows the network to dedicate most of its capacity towards coordinate prediction accuracy. Each landmark consists of the following: x and y: Landmark coordinates normalized to [0.0, 1.0] by the image width and height respectively. z: Distance between the camera and the user visibility: A value in [0.0, 1.0] indicating the likelihood of the landmark being visible (present and not occluded) in the image.
## Proposed Methodology

- FACE AND HAND DETECTION

- FACIAL AND HAND LANDMARK DETECTION

- CAPTURE THE COORDINATES OF 3D SURFACE AND GENERATE A CSV DATA

- TRAINING AND TESTING OF THE DATASET GENERATED

## Pros of Prosposed System

Real-time No need of huge dataset Fully automated Because of MediaPipe no need for common data augmentations like affine transformations consisting of rotations, translation.

## Cons of Prosposed System

Due to small dataset , it leads to overfitting We aren’t taking any measures for audio related cheating.

## Future Work

We have proposed and implemented an automated proctoring system using computer vision and MediaPipe. This study demonstrates how to avoid cheating in online examinations by employing real time proctoring based on vision capabilities.

- Add a vision-based function called facial recognition, which will ensure that no one else can take the candidate's place and administer the test in the middle.

- Detect multiple faces into a frame.


- Develop audio based proctoring system.

## Results

![Screenshot 2022-07-24 090925](https://user-images.githubusercontent.com/93306837/180631257-ef5861a7-18af-4ffd-9580-68e671183ec3.png)

![Screenshot 2022-07-24 090957](https://user-images.githubusercontent.com/93306837/180631273-bf4959c2-c548-45ae-97d0-3ec3aa02cbcc.png)

![Screenshot 2022-07-24 091034](https://user-images.githubusercontent.com/93306837/180631278-787c067e-7b13-4b9e-801a-ec04fd5ab2d6.png)

![Screenshot 2022-07-24 091100](https://user-images.githubusercontent.com/93306837/180631281-3b5ba5b6-d61f-4a09-9f37-cfff2be244ec.png)

![Screenshot 2022-07-24 091135](https://user-images.githubusercontent.com/93306837/180631284-efd6dc98-f680-4412-88de-8b2caf5fa1f5.png)











