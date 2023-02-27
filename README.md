# Emoji-Generator

### Introduction
Emojify from video is a project that involves using computer vision and machine learning techniques to detect and track facial expressions and emotions in a video and then overlay corresponding emojis onto the faces in real-time.
The project involves several steps, including:
1. Face detection and tracking: 
This involves using a computer vision algorithm to detect and track faces in a video. Once a face is detected, the algorithm will track it as it moves throughout the video. We are using CNN to do this facial detection here.

2. Emotion detection: 
This involves using a machine learning algorithm to analyze the facial expressions of the person in the video and determine their emotional state. There are several approaches to this, including using facial landmarks, extracting features from the face, and analyzing the movement of the face muscles.

3. Emojification: 
Once the emotional state of the person in the video has been determined, the appropriate emoji can be overlaid onto the video so that we can see what emotion emoji they are.


Overall, the goal of the project is to create a fun and engaging way to visualize emotions in a video, and potentially have applications in areas such as video conferencing, education, and entertainment.

### Data
1. The FER2013 dataset (facial expression recognition) consists of 48*48 pixel grayscale face images. The images are centered and occupy an equal amount of space. This dataset consist of facial emotions of following categories:
0:angry; 1:disgust; 2:feat; 3:happy; 4:sad; 5:surprise; 6:natural

You can find the dataset here in the link: https://www.kaggle.com/datasets/msambare/fer2013

2. Emoji photos: The emojis are made by myself, please find them in the data folder.

### Result:
The final result gave us a emoji generator by captioning the emotion, however, sometimes our models cannot distinguish some expressions well, probably because our epochs is not high, or our trainning dataset is not good enough.
<video src='https://user-images.githubusercontent.com/90078254/221697560-d231276c-e5e5-4f51-bc52-cbd6e64dc2c6.mov' width=80>

### Reference
Emojify – Create your own emoji with Deep Learning:

https://data-flair.training/blogs/create-emoji-with-deep-learning/
