## Title of the Project
A Real-Time Behavioral Analysis and Wellness Recommendations.

## About
Human Activity Recognition (HAR) plays a pivotal role in accurately interpreting human actions and emotions, with significant applications in medical and healthcare domains. This project aims to leverage cutting-edge deep learning techniques to enhance patient care through real-time analysis of human behavior and mood. By utilizing Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks, the project provides an innovative solution for monitoring and analyzing emotional of the people. The combination of CNNs and LSTMs enables the creation of a real-time system capable of detecting and analyzing both emotional and physical states of an individual. This system can track changes in mood, identify signs of distress, and provide immediate recommendations or alerts to healthcare providers for timely intervention.
## Features
Mood Detection and Emotional State Analysis.
High Accuracy and Precision.
Convolutional Neural Networks (CNNs) for Feature Extraction.
Long Short-Term Memory (LSTM) Networks for Sequential Analysis.
Wellness Recommendation based on the acquired emotions.
## Requirements
Hardware Requirements: Camera or Video Capture Device: To record and capture video frames for human activity recognition. Computer with a GPU: Required for running deep learning models (CNNs and LSTMs) efficiently.

Software Requirements: Operating System: Windows, macOS, or Linux (depending on your preference). Programming Languages: Python (for machine learning and video processing). Libraries/Frameworks: TensorFlow / Keras: For building and training deep learning models (CNNs and LSTMs). OpenCV: For video processing and real-time frame extraction. NumPy and Pandas: For handling data and performing basic operations. Matplotlib / Seaborn: For data visualization of the results. Scikit-learn: For any additional machine learning tasks like classification or regression.

Data Requirements: Video Datasets: Datasets of human activities and emotions -FER2013 datasets.

Modeling Requirements: CNN for Feature Extraction: To extract spatial features from video frames. LSTM for Sequential Analysis: To analyze the temporal relationships of human activities over time. Emotion Detection Algorithms: For interpreting emotional states from actions.

## System Architecture
![image](https://github.com/user-attachments/assets/1a89f466-1a30-4839-b2d4-0f0fe29ec1a6)



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Evaluation of the model

![image](https://github.com/user-attachments/assets/f7845a77-3318-48f0-a6d4-f8b5fbd067b0)
![image](https://github.com/user-attachments/assets/3eb49bb1-7e7a-4f16-a7cc-b5d1f11a7ba3)
![image](https://github.com/user-attachments/assets/ec883fd2-f656-41df-983b-bd150763d67b)





#### Output2 - Wellness Recommendations
![image](https://github.com/user-attachments/assets/8f0a4634-554f-464e-8218-54c36465b726)
![image](https://github.com/user-attachments/assets/e5f16284-ce30-4cf8-b2e9-766c26124f3c)
##### Detection Accuracy: 84.6% (nearly 85%) Test Loss: 0.487 Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
This model will enable real-time tracking of patients’ moods and behaviors, identifying patterns over time. By continuously analyzing these trends, it can deliver wellness recommendations tailored to individual emotional needs, like stress-relief exercises or sleep improvements.It will ensure reliable, real-time insights into patient behavior, enhancing the quality of monitoring.

This project stands to significantly impact healthcare by enabling real-time patient monitoring, personalized care, and a deeper understanding of mental and emotional health, ultimately leading to better patient outcomes and streamlined caregiving.


## Articles published / References
E. Ghaleb, M. Popa and S. Asteriadis, “Multimodal and Temporal Perception of Audio-visual Cues for Emotion Recognition," 8th International Conference on Affective Computing and Intelligent Interaction, 2019, pp. 552 -558.
Z. Rzayeva and E. Alasgarov, “Facial Emotion Recognition using Convolutional Neural Networks,” IEEE 13th International Conference on Application of Information and Communication Technologies 2019, pp. 1 -5.
S. R. Livingstone, F. A. Russo, “The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS):” A dynamic, multimodal set of facial and vocal expressions in North American English. PLoS ONE Vol. 13 No. 5, 2018, e0196391.
S. Bursic, G. Boccignone, A. Ferrara, A. D’Amelio, R. Lanzarotti, “Improving the Accuracy of Automatic Facial Expression Recognition in Speaking Subjects with Deep Learning.” Appl. Sci. Vol. 10, No. 11, 2020, 4002.
M. S. Hossain, G. Muhammad, “Emotion recognition using deep learning approach from audio–visual emotional big data.” Information Fusion Vol. 49, 2019, pp. 69–78.




