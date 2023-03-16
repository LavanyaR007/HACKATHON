# HACKATHON

DRIVER DROWSINESS DETECTION SYSTEM
Driver drowsiness is a severe issue that causes many road accidents every year. Drowsy driving can lead to accidents due to decreased reaction time, impaired decision-making, and impaired driving performance. This project aims to address this issue by developing a system that can detect driver drowsiness in real-time using computer vision and deep learning techniques. This system can help prevent accidents and save lives by alerting drivers when they are getting drowsy. 
The project uses a deep learning architecture to detect the status of the driver's eyes and generate an alarm if the eyes are closed more than usual. The system first detects the face using OpenCV and then detects the eyes within the face region. The deep learning model then classifies the eyes as open or closed based on the input images. If the model detects that the eyes are closed more than usual, an alarm is generated to alert the driver.
The deep learning model used in this project is trained on a dataset of open and closed-eye images using TensorFlow. The model is fine-tuned for the specific task of detecting drowsiness in drivers. The system is implemented in Python using OpenCV for video capture and processing and TensorFlow for deep-learning model training and prediction.
By detecting drowsiness in drivers in real time, this system can help prevent accidents caused by drowsy driving. Individuals can use the system, transport companies, and law enforcement agencies to ensure road safety.

Installation: To run this project, you need to install the following dependencies:
•	Python 3.x
•	TensorFlow 2.x
•	OpenCV
•	Numpy
•	Playsound (for playing the alarm sound)
Usage:
To use the driver drowsiness detection system, follow these steps:
Clone the repository to your local machine.
Open the command prompt and navigate to the project directory.
Run the "drowsiness_detection.py" file using the command "python drowsiness_detection.py"
The webcam feed will open and the system will start detecting the status of your eyes.
If the system detects that your eyes are closed more than usual, an alarm will be generated.
Training:
The deep learning architecture used in this project is trained on a dataset of open and closed-eye images using TensorFlow. You can prepare the model using your dataset or fine-tune the existing model on your dataset.
Contributors: This project is developed by [Your Name] and [Your Team Members]. If you have any suggestions or issues, please contact us.
License: This project is licensed under the [License Name] license. You can find the details in the "LICENSE" file.
Acknowledgments: We would like to thank the developers of TensorFlow and OpenCV for providing the tools to develop this project. We would also like to thank the contributors to the datasets used in this project.


![image](https://user-images.githubusercontent.com/75923059/225628518-cc8e5a5f-aeb8-402b-afc3-4b925bb7c78b.png)

![image](https://user-images.githubusercontent.com/75923059/225628589-44486ba0-16ef-4406-9664-80bed391fae9.png)
