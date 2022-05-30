# -Qatar_comp_YOLOv5_L

# The code in Colab 
https://colab.research.google.com/drive/1kSHpdxP5mCgBnz971hdNW72Qn8s9KxHR?usp=sharing
Sign language is a communication system that uses Gestures and visual signs, usually used by people who have speech or hearing difficulties. To make these people involved In the verbal communication community it is important to understand The gesture they use to communicate. Often people who do not use the gesture in real life cannot understand what the gesture is. In this paper, we propose a solution to detect the alphabet provided by each gesture. There are actually some proposed methods that use deep learning to learn sign language. However, the effective uses of these models are limited. We suggest YOLOv5 based solution because it is lightweight, fast and has good accuracy. We Used benchmark database [13] (mendly data,2018) with augmentation for training and evaluate the model, but the result was not satisfied so we changed it to another one [14] (kaggle,2022)  . We achieved 99.4% precision ,99.5% recall, 99.3% map@0.5 . ,86.3% map@0.5: 0.95 scores which is enough in real-time gesture recognition.

#click here to see the smart model
[![click here to see the smart model](https://github.com/Alrehawi/Qatar_comp_YOLOv5/blob/main/sheen.png)](https://www.youtube.com/embed/y_ViyiNd_0Y)
# Arabic sign language - letters
[![ARSlang ](https://github.com/Alrehawi/-Qatar_comp_YOLOv5_L/blob/main/Signs_32_New.png)

# The result was:
[![Result ](https://github.com/Alrehawi/-Qatar_comp_YOLOv5_L/blob/main/results.png)

To run model on the webcam :
# python detect.py --source 0 --weights best.pt


