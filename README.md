# Social Distancing Analyzer

## Overview

<b>Social distancing</b> is deliberately increasing the physical space between people to avoid spreading illness. Staying at least six feet away from other people lessens your chances of catching <b>COVID-19</b>. This project uses OpenCV and YOLO to monitor/analyze whether people are maintaining social distancing or not.

<ul>
  <li>This project uses YOLO for object detection.</li>
  <li>Once the objects(people) are detected it then draws a bounding box around them.</li>
  <li>Using the centroid of the boxes we then measure the distances between them.</li>
  <li>For the distance measure, <b>Euclidean Distance</b> was used.</li>
  <li>A box is colored RED if unsafe and GREEN if safe.</li>
</ul>



## Demo

Output video

![](output/output.gif)

## Limitations and Future Scope

<ul>
  <li>This project does not take into account the camera perspective.</li>
  <li>It does not leverage a proper camera calibration (Distances are not measure accurate).</li>
</ul>

&nbsp;<b><i>Will work on these limitations.</i><b>

## References

<ul>
  <li><a href="https://www.pyimagesearch.com/start-here/">Getting started with OpenCV</a></li>
  <li><a href="https://pjreddie.com/darknet/yolo/">YOLO for Object Detection</a></li>
</ul>




Also, do give my medium article a read! <a href="https://medium.com/@tanibhamajumder/social-distance-analyzer-5a6dd214aedf">Click Here</a>

<b><i>PS: This is my first OpenCV project. Will work on more in the future.</i><b><br></br>
<b><i>PPS: Stay Home and Stay Safe!😊 </i><b>

<br>
&copy;tanibha majumder2021
# socail-distance-Analyzer-1
