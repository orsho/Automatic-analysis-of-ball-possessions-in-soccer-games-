# Automatic analysis of ball possessions in soccer games using computer vision methods

Paper [Automatic analysis of ball possessions in soccer games](https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Automatic%20Analysis%20of%20Ball%20Possessions%20in%20Soccer.pdf) 

Nowadays, ball possession percentages in a soccer game are calculated manually by the sum of passes of each team divided by the game total passes in the game. This method has been found correlated with the actual ball possessions of most games but not in teams that make a lot of passes during the game and are considered well above average in this parameter. 

In our research, we are trying to measure it automatically by classifying which team possesses the ball in each frame, based on computer vision techniques, and without using deep learning models (course restrictions). 

There are numerous challenges in this research e.g. illuminations, occlusions, small, fast and unpredicted ball movement, moving camera and more. In order to measure possessions correctly we explored different object detection and object tracking techniques. 

Our best results achieved by a combination of several heuristics which are mainly based on Region-based and Mean-Shift. Our algorithm produced decent results even compared to DL models that were trying to solve this problem. The project was ranked 1st out of 100 projects submitted in the course.  

<img src="https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/5d2888b62658a0da7202d94c3da57e279efabd91/Images/measure.JPG" width="300" height="300">

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

<img src="https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/29cda6a6a1b917b4a41a38622760e06ca9a19baf/Images/Algo%20arch.JPG" width="900" height="400">

## Final results

For evaluating, we observed on each frame in each video and divide our observations into the next confusion matrix:

<img src="https://https://github.com/orsho/Automatic-analysis-of-ball-possessions-in-soccer-games-/blob/main/Images/eval.GIF" width="750" height="500">

[Link to all video results](https://drive.google.com/drive/folders/1J6P6w-ALf77sT4xX5981NvOzzJoJS-Ib?usp=sharing) 


