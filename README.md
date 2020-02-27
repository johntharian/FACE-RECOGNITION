# FACE-RECOGNITION
face recognition with opencv

generate dataset -> train model -> recognition
For generating dataset, open the face_dataset.py file with idle and rn it.
It will generate images and it will be  stored in the dataset folder.

training dataset-> open the face_trainning.py file and run it.
The error it's showing is

Traceback (most recent call last):
  File "C:\Users\John\Desktop\FACE-RECOGNITION\FacialRecognition\02_face_training.py", line 10, in <module>
    import cv2
  File "C:\Users\John\AppData\Roaming\Python\Python38\site-packages\cv2\__init__.py", line 3, in <module>
    from .cv2 import *
ImportError: DLL load failed while importing cv2: %1 is not a valid Win32 application.
  
  
for recognising the already existing user run the face_recognition.py file. 
