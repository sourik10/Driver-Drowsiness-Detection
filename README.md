# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.
<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>

<h3> The working of the project</h3>
<p>we have implemented a digital library that have 68 landmark detection technique. In this technique we first plot a human face with 68 points and based on 
those points we find a ratio using a mathematical equation and if that value crosses a threshold then we generate an alram which will alert the driver that he is 
in sleepy or drowsy state to avoid any kind of accidents. We have also implemented haarcascade and then we found that Dlib gives more accurate result with 
accuracy of 93%. So after ploting the points on the face we will calculate distance using mathematical algorithm. Time and distance is mainly calculated based on the points 
marked on each eye too see if the eyes are just flipping or in a drowsy state by noticing the time. If it crosses a certain threshold suppose 6sec. and stays under 10sec
then we will say the driver is in the drowsy state or if it crosses 10 sec then we will say driver is in sleepy state and raise an alert.
This is all about our technical part now sourik will conclude the project.
</p>
<h2> Active State</h2>
<center>
  <img src="https://github.com/sourik10/Driver-Drowsiness-Detection/blob/main/screenshots/fy_ss1.PNG" align="center" height="350">
</center>
 <h2> Drowsiness Alert </h2>
<center>
  <img src="https://github.com/sourik10/Driver-Drowsiness-Detection/blob/main/screenshots/fy_ss2.PNG" align="center" height="350">
</center>
