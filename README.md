# Facial-Expression-Recognition
Used Kaggle FER2013 dataset and built the Facial emotion recognition using Keras and added a real time Webcam implementation Download here https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge

# Dependency
(used a virtual environment)

`pip install Keras`

`pip install Tensorflow`

`pip install Opencv`

# Usage
For real time facial emotion recognition, execute command:
`python3 realtime_facial_expression.py`

For detecting the facial expression in a test image you can execute the command:
`python3 image_test.py test.jpg`

Used a CNN based appoach for the detection of facial expressions. The code for the CNN model is in the [Facial_CNN.ipynb](https://github.com/arnav8/Facial-Expression-Recognition/blob/master/Facial_CNN.ipynb).
The Trained model is [Present here](https://github.com/arnav8/Facial-Expression-Recognition/blob/master/model_5-49-0.62.hdf5) give an accuracy of approximately 90% after training for 200 epochs and an accuracy of 65% for 30 epochs.

# Image testing example
![alt text](https://github.com/arnav8/Facial-Expression-Recognition/blob/master/result_emotion_detection_arnav.jpg "Logo Title Text 1")

# Acknowledgement
http://sefiks.com/2018/01/01/facial-expression-recognition-with-keras/

