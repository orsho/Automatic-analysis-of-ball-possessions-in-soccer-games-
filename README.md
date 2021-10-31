# Automatic analysis of ball possessions in soccer games using computer vision methods

Paper [Automatic analysis of ball possessions in soccer games](https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Automatic%20Analysis%20of%20Ball%20Possessions%20in%20Soccer.pdf) 

Nowadays soccer ball possession is computed manually by the sum of passes for each team
divided by the game total passes to produce a percentage of ball possession.
This method has been found correlated with the actual ball possession of most games but not in
teams that make a lot of passes during the game like Barcelona.
In this project, we are trying to measure it automatically by classifying which team possesses
the ball in each frame, based on computer vision techniques.
There are numerous challenges in this problem, including: changing grass colors and
illumination, moving camera, occlusions, small soccer ball, interfering field marks in the color of
the ball, ball moving at different directions and speed, ball shape distortion at frames due to high
speed, ball changing size with respect to distance from the camera and more.

<img src="https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Images/stats%20measured.JPG" width="500" height="200">

## Highlighted features

* This project uses OpenCV and Python main libraries
* We needed to classify which team possesses the ball in each frame, based on computer vision techniques without using advanced neural networks
* All code is arranged in one [Jupyter notebook](https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/The%20notebook.ipynb)
* The notebook will work on any python IDE environment but it is best to open it in Jupyter notebook
* You should download the data folder in order to run the notebook or add videos from your own

## Algorithm

Our algorithm divides into 3 main parts:

* Detect the ball and tracking it
* Players detection and classification
* Calculate ball possession in each frame and aggregate it

**Technical diagram of our project**

<img src="https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Images/diagram_algo.JPG" width="600" height="700">

## Final results

For evaluating, we observed on each frame in each video and divide our observations into the next confusion matrix:

<img src="https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Images/confusion%20matrix.JPG" width="750" height="500">

[Link to all video results](https://drive.google.com/drive/folders/1J6P6w-ALf77sT4xX5981NvOzzJoJS-Ib?usp=sharing) 


