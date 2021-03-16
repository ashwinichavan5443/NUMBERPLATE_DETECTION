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
<b>Step 2 : Edit labelMap.pbtxt file according to objects we want to detect</b><br>
leave everything as it is and create zip file of this folder and upload it on drive<br>
<br>
<b>Step 3 : After completing all the configurations run the following colab book for traning custom model</b><br> 
ssdlite_objectdetection_traning.ipynb
<br>
<b><h3>OutPut:</h3></b><br>
<img src="https://github.com/ashwinichavan5443/NUMBERPLATE_DETECTION/blob/master/result1.jpg"></img><br>
<p>For exctracting character from detected numberplate visit following git repository</p>
<a href="https://github.com/ashwinichavan5443/Numberplate_character_recognition_using_Tesseract">https://github.com/ashwinichavan5443/Numberplate_character_recognition_using_Tesseract>Numberplate_character_recognition_using_Tesseract</a>
