
# UDACITY OPENVINO EDGE-AI CERTIFIACTION

 This scholorship was provided by Udacity. It was 5-lesson plan which provided insight how to make Edge application which make deeep learning model run locolly on the device. OpenVINVO tool allows us to convert a deep learning model and configure it to run on a specialized hardware.

### Why Edge Application?
Defined as edge computing as “a part of a distributed computing topology in which information processing is located close to the edge – where things and people produce or consume that information.”

###  1. Infrence from Video
This folder cantains a project which analize the [video](https://github.com/simratsingh14/open_vino_udacity/blob/master/infrences%20fromv%20ideo/pets.mp4)  and return the time two particular set of pets are in camera scene and returns the timestamp when a particular event occours.

File contained are:-
1. model.xml:- xml reprenstaion of Deep Learning Model used as a infrence to model
1. model.bin:- bin reprenstaion of Deep Learning Model
1. Annotation 2020-03-13 201346.png:- Screenshot of image
1. app.py :- Main file of python
 

###  2. integrating-on -web
In this project, Data was transfered from Edge Application to the web Server using **MQTT** and **FFmpeg servers**.
[Input video](https://github.com/simratsingh14/open_vino_udacity/blob/master/integrating-on%20-web/test_video.mp4) was converted to [output video](https://github.com/simratsingh14/open_vino_udacity/blob/master/integrating-on%20-web/test_video.mp4) and was dispalyed along with data like **speed** and **classes counted** from JSON server


File contained are:-
1. app.py :- Main file of python
1. infrence.py:- supporting file for app.py
1. Capture.PNG:- Screenshot of server with video server
1. test_video.mp4:- Input video given to program
1. out_example.mp4 :- output video seen on server


### Library Used:-
1. OpenVino toolkit 
1. openCV for image processing
1. Numpy
1. ensorflow
1. paho.mqqt
