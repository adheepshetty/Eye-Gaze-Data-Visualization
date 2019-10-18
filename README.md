# Eye-Gaze-Data-Visualization

The aim of this assignment is to show participant five's gaze in the form of visualization and answer following questions on the basis of visualization:
<ol>
 <li>Did the user struggle more when searching or processing the given visual information?
 <li>Was the user more successful at completing the given task when using one visual support than the other?
 <li>How long was the user’s eyes were fixated at a particular point?   
</ol>
<p>The goal of this assignment is to provide interactive visualization support to users who are interested in explorative activities, e.g. finding “interesting” things, examine the dataset by exploring whether a particular feature/trend/pattern is present, etc. </p>

## Rough Plan

## Input Files
p5 - Participant 5
graph - Participant is looking at Graph Visualization.<br>
tree - Participant is looking at Tree Visualization.<br>
EVD - Data of Events that is done by the participant.<br>

FXD - Fixation data shows for how long participant's eyes were fixated.<br>

GZD - Gives information about participant's gaze like his/her pupil size distance from screen.<br>

### Files:
<ul>
  <li>p5.graphEVD
   
   ![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Data/ssevd.PNG)
   
   
  <li>p5.graphFXD
 
   ![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Data/ssfxd.PNG)
   
  <li>p5.graphGZD
 
   ![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Data/ssgzd.PNG)
   
  <li>p5.treeEVD
  <li>p5.treeFXD
  <li>p5.treeGZD
  <li>p5GZD
</ul>

## Output Files

Output files are HTML pages showing the visualization of gaze of participant according to time interval.
## Files

<ul>
 <li>graph-visualization.HTML
 <li>tree_visualization.HTML
</ul>
 
## Design

![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/RoughPlan.png)

## Technology Used

We used python for visualization. Python was chosen since it has modules like pandas, numpy which can be used for data manipulation i.e data preprocessing. Even, it is easy to do analysis of data by visualiznig it using module name plotly. So the list of modules used are:
<ol>
 <li> Plotly
 <li> Pandas
 <li> Numpy
</ol>

## Team Members

<ul>
 <li> Adheep Shetty
 <li> Saumya Shrivastav
 <li> Sylviana Mahaut
 <li> Kai 
 <li> Pamela Regudo
</ul>
 
 
## Challenges Faced

### Challenge #1:

The time slide duration was more hence more points on the screen at this point hence we have to increase this duration or frames to visualize the pattern and points more precisely.

[![IMAGE ALT TEXT](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Challenges/challenge1img.PNG)](https://www.youtube.com/watch?v=k8maCYvtNA0&feature=youtu.be)


### Challenge #2:

The challenge faced during Eye Gaze dataset visualization was initially with the slides the traces were added but older traces were not removed. Therefore the screen got busier as the time passed.

[![IMAGE ALT TEXT](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Challenges/challenge2img.PNG)](https://www.youtube.com/watch?v=_O_Qppccgu0&feature=youtu.be)


### Challenge #3:

The challenge we faced when we were trying to find the scanpath over the time is that the Screen appeared scribbled.

![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/Challenges/challenge3img.png)


## Screenshot of Visualizations

### Graph Visualization

![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/HTML%20pages/graph-viz.PNG)

### Tree Visualization

![alt text](https://github.com/adheepshetty/Eye-Gaze-Data-Visualization/blob/master/HTML%20pages/tree-viz.PNG)
