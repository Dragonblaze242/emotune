# Emotune
Emotune is a *realtime facial expression based music player* which captures the facial expression in real-time and plays music accordingly. (This project was part of CSI Paper Presentation)

## Samples
<img width="601" alt="emotune_3" src="https://github.com/spndnqq/emotune/assets/135336929/89294096-2e66-451d-842a-bb1bfcf31262">
<img width="601" alt="emotune_2" src="https://github.com/spndnqq/emotune/assets/135336929/3cb849ec-cae1-4ca4-b433-364c3a3b9737">
<img width="601" alt="emotune_1" src="https://github.com/spndnqq/emotune/assets/135336929/a3ab0c57-858b-4640-b8e3-7aa262f2569a">

## Features
-	This is complete GUI based application.
-	Created using Python and Deepface, Kivy, OpenCV libraries.
-	The webcam is accessed by OpenCV and face is captured through Haar Cascade Classifier.
-	Then facial expressions are compared with predefined models to get the emotion. Here lightweight library Deepface is used.
-	This GUI base is created by Kivy. After getting the emotion the correct music is played by Kivy.

## Dependencies
- OpenCV
- Kivy
- TensorFlow
- Deepface

```
pip install -r requirements.txt
```
