# REAL-TIME-VISION-PROCTORING

Real time automated vision proctoring using Computer Vision and Machine Learning.

## Using MediaPipe Framework

MediaPipe ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate 3D surface via regression. It allows the network to dedicate most of its capacity towards coordinate prediction accuracy. Each landmark consists of the following: x and y: Landmark coordinates normalized to [0.0, 1.0] by the image width and height respectively. z: Distance between the camera and the user visibility: A value in [0.0, 1.0] indicating the likelihood of the landmark being visible (present and not occluded) in the image.MediaPipe ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate 3D surface via regression. It allows the network to dedicate most of its capacity towards coordinate prediction accuracy. Each landmark consists of the following: x and y: Landmark coordinates normalized to [0.0, 1.0] by the image width and height respectively. z: Distance between the camera and the user visibility: A value in [0.0, 1.0] indicating the likelihood of the landmark being visible (present and not occluded) in the image.
## Proposed Methodology

- FACE AND HAND DETECTION

- FACIAL AND HAND LANDMARK DETECTION

- CAPTURE THE COORDINATES OF 3D SURFACE AND GENERATE A CSV DATA

- TRAINING AND TESTING OF THE DATASET GENERATED
