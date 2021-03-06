ABOUT:

Faces is a facial and sentimental recognition program. Through the input  of small video files, the Faces program is able to grab various images and locate faces, analyze the current facial emotion, and report a sentimental score based on the analyzed expression. 


Components:

Faces is built through a Python framework with the assistance of web services. Faces makes use Google Cloud APIs such as Google Vision. Faces also uses the Django Python web framework for maintaining the web services and also an internal database. Faces uses FFmpeg to break down video files into a subfolder of image captures. 


Methodology:

Faces uses a web presence where the user can upload a video file to score. The video file is broken down into a sub-folder of image captures that range from a pre-determined time gap. The program cycles through each image with the face detection sequence. If a successful face detection occurs, Faces will visibly locate the face in the image and process a sentimental score based off of the expression. The image is then left in the sub-folder to be viewed by the user. An overall video score is calculated and also a overall graphical view of the scoring process is outputted. 


Results:

Faces successfully and consistently executes a facial and sentimental recognition process. Faces is capable of processing video files, distinguishing faces from images, processing emotional expressions, and visibly displaying results to the user. 


Conclusion:

Faces initially was exclusive to the Google App Engine API. Due to difficulties, a transition deemed necessary. Through research and trial, the Django framework proved to provide all necessary features. With the use of all components, Faces successfully accomplishes its original objectives and can be carried onward to bigger and better goals. 



