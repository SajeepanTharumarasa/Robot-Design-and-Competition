# Robot Design and Competition - 2021 Team: Yadkai

 ## The tasks of the competition.
 <div class="row">
  <div class="column">
 <img style="width:100%" alt="snow" src="https://user-images.githubusercontent.com/66894143/201977980-a7c7d974-a02a-4864-b63a-cf6124ef0e04.PNG">
   </div>
  
</div>

 
 <ul><li>
 Line following
 <ul> <li>
 the robot must follow a white line on a black surface. These paths may contain straight
 lines, curved lines, or dotted line segments.
 </li></ul>  </li>
 <li>
 Wall maze
 <ul> <li>
  After a line following section, the robot will have to navigate through a wall maze
 section. This maze will not contain any looping paths. (A single possible path from
 start to end is guaranteed.)
  </li></ul>  </li>
 <li>
 Mosaic Floor Area
  <ul> <li>
 The robot exiting the wall maze should immediately enter the mosaic floor area and
 proceed to complete the following subtasks. Inserting the key solids to respective
 keyholes to close the bridge. Collecting the ball of the color assigned to your team at
 the start of the competition.
 </li></ul>  </li>
 <li>
 Bridge
  <ul> <li>
 The robot should cross the closed bridge and exit the area to a dotted line segment.
   </li></ul>  </li>
 <li>
 Shooting area
  <ul> <li>
 The robot must choose the correct path at the Y junction area according to the color
 assigned. While staying in the restricted space, the robot will have to shoot the
 collected ball through the goal.
   </li></ul>  </li></ul>


## The Task Follow & Approch

![Algorithm - Frame 6](https://user-images.githubusercontent.com/66894143/201981973-b707f79f-28df-4089-b2ec-02ca5b5b0f63.jpg)


## Algorithm

![Algorithm - PID Line Following](https://user-images.githubusercontent.com/66894143/201982655-d6d0dca0-1604-412f-80fd-427cfd7f04d8.jpg)

<div class="row">
  <div class="column">
    <img src="[img_snow.jpg](https://user-images.githubusercontent.com/66894143/201982655-d6d0dca0-1604-412f-80fd-427cfd7f04d8.jpg)" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="[img_forest.jpg](https://user-images.githubusercontent.com/66894143/201982655-d6d0dca0-1604-412f-80fd-427cfd7f04d8.jpg)" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="[img_mountains.jpg](https://user-images.githubusercontent.com/66894143/201982655-d6d0dca0-1604-412f-80fd-427cfd7f04d8.jpg)" alt="Mountains" style="width:100%">
  </div>
</div>


The complete report (downloadable) can be found [ here](https://github.com/sanjith1999/Analog-Piano/blob/master/Submission%20Files/Report/main.pdf)
<br>
<br>



### Breadboard Design
<img src="./Results/breadboard.jpg" alt = " Breadbord Design" width="200"/>
<br>
<br>
<h3>Prototype</h3>
<img src="./Results/oscillator_pcb.jpg" alt = " Prototype Wave Generator" width="150"/>
<img src="./Results/dot.jpg" alt = " Breadbord Design" width="250"/>
