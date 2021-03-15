# NUMBERPLATE_DETECTION

<b>For traning custom object detection following are steps:</b><br>
<b>Step 1: Collect dataset</b><br>
-dataset folder structure should be like:<br>
-images<br>
       |-train<br>
       |-test  <br>
distribute data in 80% - 20%
<br>
<br>
<b>Step 2: Edit labelMap.pbtxt file according to objects we want to detect</b><br>
<br>
leave everything as it is and create zip file of this folder and upload it on drive<br>
<br>
After completing all the configurations run the following colab book for traning custom model<br> 
<a href="https://colab.research.google.com/drive/1WM8xLkyLN9KOAqhoPbsvcjGYtRQ1J-x8#scrollTo=OY23YrKYgI14">ssdlite_objectdetection_traning.ipynb</a>
