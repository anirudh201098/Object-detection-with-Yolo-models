# Object-detection-with-Yolo-models
The goal is to recognize objects from a number of visual object classes in realistic scenes (i.e. not pre-segmented objects). It is fundamentally a supervised learning learning problem in that a training set of labelled images is provided. The twenty object classes that have been selected are:

    Person: person
    Animal: bird, cat, cow, dog, horse, sheep
    Vehicle: aeroplane, bicycle, boat, bus, car, motorbike, train
    Indoor: bottle, chair, dining table, potted plant, sofa, tv/monitor

Dataset used: [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)




## Loss function of Yolo on [PASCAL VOC 2012 dataset](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)
![alt text](https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/Loss.png)

## mean Average Precision(mAP) function of Yolo on [PASCAL VOC 2012 dataset](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html) 
![alt text](https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/map.png)

## Predictions
### Yolo version-1 predictions after 40k epochs
<img src="https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo1.jpg" width="400" height="400>

### Yolo version-2 predictions after 40k epochs
![alt text](https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo2.jpg)

### Yolo version-3 predictions after 40k epochs
![alt text](https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo3.jpg)

### Yolo version-4 predictions after 40k epochs
![alt text](https://github.com/anirudh201098/Object-detection-with-Yolo-models/blob/main/Predictions%20and%20graphs/yolo4.jpg)


### [Yolo version-1 predictions on a video](https://drive.google.com/file/d/1-IxaZj_W6y7kgcDEB2d9Z0kTUvlMGnS0/view?usp=sharing)

### [Yolo version-2 predictions on a video](https://drive.google.com/file/d/1-HFbRBNCg2TQk19XXz-HZebMg3CXFSPu/view?usp=sharing)

### [Yolo version-3 predictions on a video](https://drive.google.com/file/d/1-GAXnvMBKJm5X4IgBy4nQfw0Qbnl9ujL/view?usp=sharing)

### [Yolo version-4 predictions on a video](https://drive.google.com/file/d/1-TkFoi7TPFB7_36EJUXXdloGtOxUylbz/view?usp=sharing)

#### References
[1] [Yolo-1 paper](https://arxiv.org/pdf/1506.02640.pdf) 

[2] [Yolo-2 paper](https://arxiv.org/pdf/1612.08242.pdf)

[3] [Yolo-3 paper](https://pjreddie.com/media/files/papers/YOLOv3.pdf)

[4] [Yolo-4 paper](https://arxiv.org/pdf/2004.10934.pdf)

[5] https://pjreddie.com/darknet/yolo/

[6] https://github.com/AlexeyAB/darknet

