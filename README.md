# Face_Emotion_Recognition
# Real-Time-Face-Emotion-Recognition

Emotion recognition is the process of identifying human emotion. People vary widely in their accuracy at recognizing the emotions of others. Use of technology to help people with emotion recognition is a relatively nascent research area. Generally, the technology works best if it uses multiple modalities in context. To date, the most work has been conducted on automating the recognition of facial expressions from video, spoken expressions from audio, written expressions from text, and physiology as measured by wearables.

Facial expressions are a form of nonverbal communication. Various studies have been done for the classification of these facial expressions. There is strong evidence for the universal facial expressions of seven emotions which include: neutral happy, sadness, anger, disgust, fear, and surprise. So it is very important to detect these emotions on the face as it has wide applications in the field of Computer Vision and Artificial Intelligence. These fields are researching on the facial emotions to get the sentiments of the humans automatically.
![image](https://github.com/Gauravgade3/Real-Time-Face-Emotion-Recognition/blob/main/images/kid-expressions-cover%20(1).jpg)

## Problem Statements

The Indian education landscape has been undergoing rapid changes for the past 10 years owing to the advancement of web-based learning services, specifically, eLearning platforms.

Global E-learning is estimated to witness an 8X over the next 5 years to reach USD 2B in 2021. India is expected to grow with a CAGR of 44% crossing the 10M users mark in 2021. Although the market is growing on a rapid scale, there are major challenges associated with digital learning when compared with brick and mortar classrooms. One of many challenges is how to ensure quality learning for students. Digital platforms might overpower physical classrooms in terms of content quality but when it comes to understanding whether students are able to grasp the content in a live class scenario is yet an open-end challenge. In a physical classroom during a lecturing teacher can see the faces and assess the emotion of the class and tune their lecture accordingly, whether he is going fast or slow. He can identify students who need special attention.

Digital classrooms are conducted via video telephony software program (ex-Zoom) where it’s not possible for medium scale class (25-50) to see all students and access the mood. Because of this drawback, students are not focusing on content due to lack of surveillance.

While digital platforms have limitations in terms of physical surveillance but it comes with the power of data and machines which can work for you. It provides data in the form of video, audio, and texts which can be analyzed using deep learning algorithms.

Deep learning backed system not only solves the surveillance issue, but it also removes the human bias from the system, and all information is no longer in the teacher’s brain rather translated in numbers that can be analyzed and tracked.

I will solve the above-mentioned challenge by applying deep learning algorithms to live video data. The solution to this problem is by recognizing facial emotions.
## Dataset link 
https://www.kaggle.com/msambare/fer2013
# Dependencies
* Tensorlow
* Keras
* Opencv
* Streamlit
# Setup
## You need  the Following:
Python and the following packages:
* OpenCV 
* Keras (with Tensorflow backend)
* Tensorflow
* Numpy
* pandas
* Matplotlib
* sklearn
![image](https://github.com/Gauravgade3/Real-Time-Face-Emotion-Recognition/blob/main/images/Screenshot%202022-03-22%20103022.jpg)
Since there was an soft limit size of 300MB on heroku colud platform to perfectly deploy and run the model through app. My model size was around 492MB because of which i can only deploy the app but couldn't run perfectly. So this can be solved by providing some more extra space or by further reducing the slug size of model if possible.

# Demo Video Captures
![image](https://github.com/Gauravgade3/Real-Time-Face-Emotion-Recognition/blob/main/images/Emotion%20Detector%2022-03-2022%2011_19_23.png)
![image](https://github.com/Gauravgade3/Real-Time-Face-Emotion-Recognition/blob/main/images/Emotion%20Detector%2022-03-2022%2011_19_35.png)
![image](https://github.com/Gauravgade3/Real-Time-Face-Emotion-Recognition/blob/main/images/Emotion%20Detector%2022-03-2022%2011_20_35.png)
# Here is my deployed app link :
https://face-emotion-recognition1.herokuapp.com/
