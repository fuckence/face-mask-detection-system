Problem: 
The Mask Detection System aims to build a system that detects whether individuals are wearing masks in images or live video streams. The goal is to enhance public safety by identifying compliance with mask-wearing guidelines, especially during situations like the COVID-19 pandemic. 

Background Information: 
With the emergence of COVID-19, mask detection systems have become increasingly important in various settings, including public spaces, transportation hubs, and workplaces. These systems typically employ computer vision techniques to analyze images or video frames and identify whether individuals are wearing masks. 

Data and Methods:
Information about the data:
The dataset used in this project comprises images categorized into two classes: 'with_mask' and 'without_mask'. Each image represents a person's face either wearing a mask or not wearing a mask. The dataset is collected from various sources, including online repositories and self-generated images.
Dataset: https://humansintheloop.org/resources/datasets/medical-mask-dataset/

Data Analysis and Visualizations:
Data Distribution: The dataset contains a total over 6000 images and 20 classes, and we have used only 900 images labeled as 'with_mask' and 900 images labeled as 'without_mask'. This distribution helps understand the class balance and potential biases, also accelerates the processing time.
Prior to implementing the face mask detection system, we conducted a thorough data analysis to prepare and train a model using our dataset. This crucial step involved assessing the validation accuracy and uncovering underlying patterns within the data. 

Here are several visualizations generated during the data analysis phase:

![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/d26a7d92-83b0-44ec-872c-afcf2635dc68)
![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/724c27b5-752c-4aac-88ae-3ed784442395)

Besides matplotlib.pyplot, the code also utilizes several components from the TensorFlow and Keras libraries for building and training a convolutional neural network (CNN) model for face mask detection and google colab library for using google drive.

![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/a28c1cb7-2cc9-4ae7-8a4b-d9dd937b1fdd)
![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/7c66aa72-d018-4950-9ad1-1f7f5b24fc33)

The code defines a CNN model, compiles it with appropriate settings, and trains it using the provided data generators, ultimately providing insights into the model's performance through training history.

![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/df0ef782-c45a-4953-9447-b57a0a098cbf)

Result:
The face mask detection system project is designed to improve public safety by automatically identifying individuals not wearing masks in various environments such as public transportation, retail stores, and workplaces. Using advanced computer vision technology and machine learning algorithms, the system determines whether a person's face is covered by a mask or not, thereby ensuring compliance with mask requirements and regulations.

![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/2e01a3f5-b058-404c-9e7c-4242fd1a80a5)

As it can be seen, here the validation accuracy is more than 0.8, it means our designed model will identify a person wearing mask or not without any difficulties.

![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/f9c8a684-ad67-4013-a43b-aac4ad89d712)
![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/064b366f-de2f-4b29-97de-20254ea17e9a)
![image](https://github.com/Ibranuraliev/adv-prog-final/assets/151869662/a13b7fd8-bc04-4bf9-89bb-64db95a2c0d5)

Discussion:
Our results mark a substantial advancement in enhancing the mask detection experience for users. Leveraging sophisticated computer vision algorithms and meticulous data analysis, we are dedicated to refining our mask detection system. Future iterations will prioritize rectifying any limitations identified in our current implementation and integrating user feedback to enhance the accuracy and usability of the system. Through continuous refinement and adaptation, we aim to contribute significantly to public safety efforts by providing an effective and reliable tool for monitoring mask compliance in various settings.







