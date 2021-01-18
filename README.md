# Object-detection-with-Yolo-models
The goal was to recognize objects from a number of visual object classes in realistic scenes. It is fundamentally a supervised learning learning problem in that a training set of labelled images is provided. The twenty object classes that have been selected are:

    Person: person
    Animal: bird, cat, cow, dog, horse, sheep
    Vehicle: aeroplane, bicycle, boat, bus, car, motorbike, train
    Indoor: bottle, chair, dining table, potted plant, sofa, tv/monitor

Dataset used: [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)

# Object detection
It is the task of correctly recognizing and efficiently locating multiple objects in an image automatically, by a supervised machine, given a sufficiently large training set, while avoiding false predictions and multiple bounding boxes of the same object.

# Categories of Object detectors:
● Single stage Object detectors
● Two stage object detectors

# Two stage object detectors
The architecture for most of the object detectors of this type has the following stages:
● First stage is responsible for generating region of interest using Region Proposal Network (RPN),

● In the second stage, the network is responsible for optimizing the classification and bounding boxes for the proposed region.
Some of the two stage object detection algorithms are

● R-CNN

● Fast R-CNN

● Faster R-CNN

● Feature Pyramid Network

# One stage object detectors
Single stage object detectors have a single deep network to predict the bounding boxes as well as object confidence score. In one stage object detectors the image is passed through a single network for classification and localization. And has the intuition that localization is a regression problem.
Some of the one stage object detection algorithms:

● YOLO

● YOLO (v2)

● YOLO(v3)

● YOLO(v4) 


## Predictions on Images
### Yolo version-1 predictions after 40k epochs
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo1.jpg" width="450" height="300">

### Yolo version-2 predictions after 40k epochs
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo2.jpg" width="450" height="300">

### Yolo version-3 predictions after 40k epochs
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo3.jpg" width="450" height="300">

### Yolo version-4 predictions after 40k epochs
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo4.jpg" width="450" height="300">

### Loss function of Yolo versions on [PASCAL VOC 2012 dataset](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/Loss.png"  width="500" height="400">

### mean Average Precision(mAP) of Yolo versions on [PASCAL VOC 2012 dataset](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html) 
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/map.png"  width="500" height="400">



## Predictions on Videos
### [Yolo version-1 predictions on a video](https://drive.google.com/file/d/1-IxaZj_W6y7kgcDEB2d9Z0kTUvlMGnS0/view?usp=sharing)

### [Yolo version-2 predictions on a video](https://drive.google.com/file/d/1-HFbRBNCg2TQk19XXz-HZebMg3CXFSPu/view?usp=sharing)

### [Yolo version-3 predictions on a video](https://drive.google.com/file/d/1-GAXnvMBKJm5X4IgBy4nQfw0Qbnl9ujL/view?usp=sharing)

### [Yolo version-4 predictions on a video](https://drive.google.com/file/d/1-TkFoi7TPFB7_36EJUXXdloGtOxUylbz/view?usp=sharing)

## Yolo weights

#### [Yolo-1 weights file](https://drive.google.com/file/d/10gGE2AMKtTjIj40zyEqlkRYQPaQ8gu7U/view?usp=sharing)


#### [Yolo-2 weights file](https://drive.google.com/file/d/10bfZVCsFxu88ENTElGyl_kYdPmDSeXbe/view?usp=sharing)


#### [Yolo-3 weights file](https://drive.google.com/file/d/1-Bd76ZWfzlYP44LDO1F1lD5RQsihMZ45/view?usp=sharing)


#### [Yolo-4 weights file](https://drive.google.com/file/d/1-j1scUl-Qzpg7QeBcW7fQCaBuioELxvY/view?usp=sharing)


#### References
[1] [Yolo-1 paper](https://arxiv.org/pdf/1506.02640.pdf) 

[2] [Yolo-2 paper](https://arxiv.org/pdf/1612.08242.pdf)

[3] [Yolo-3 paper](https://pjreddie.com/media/files/papers/YOLOv3.pdf)

[4] [Yolo-4 paper](https://arxiv.org/pdf/2004.10934.pdf)

[5] https://pjreddie.com/darknet/yolo/

[6] https://github.com/AlexeyAB/darknet

