# Emotune
Emotune is a *realtime facial expression based music player* which captures the facial expression in real-time and plays music accordingly. (This project was part of CSI Paper Presentation)

## Samples

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
