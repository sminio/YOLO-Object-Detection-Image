# YOLO-Object-Detection-with-OpenCV
Object detection using YOLO object detector

### Detect objects in images using Deep Learning, OpenCV, and Python.

I'll use YOLOv3 in this project, in particular, YOLO trained on the COCO dataset.

The COCO dataset consists of 80 labels, including, but not limited to:

- People
- Bicycles
- Cars and trucks
- Airplanes
- Stop signs and fire hydrants
- Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few
- Kitchen and dining objects, such as wine glasses, cups, forks, knives, spoons, etc.
…and much more!

You can find the full list of what YOLO trained on the COCO dataset can detect <a href="https://github.com/pjreddie/darknet/blob/master/data/coco.names" target="_blank"><b>using this link.</b></a>

- yolo-coco : The YOLOv3 object detector pre-trained (on the COCO dataset) model files. These were trained by the <a href="https://pjreddie.com/darknet/yolo/" target="_blank"> <b>Darknet team.</b> </a>

- yolo-coco/yolov3.weights : You can download yolov3.weights <a href="https://pjreddie.com/media/files/yolov3.weights">here</a>

## Installation

- `pip install numpy`
- `pip install opencv-python`

## To Run the project

- `python yolo.py --image images/baggage_claim.jpg`

## Screenshots
![Image](/1.png)

Here you can see that YOLO has not only detected each person in the input image, but also the suitcases as well!

Furthermore, if you take a look at the right corner of the image you can notice that YOLO has also detected the handbag on the lady’s shoulder.

![Image](/2.png)

YOLO can detect each of the players on the pitch correctly, including the soccer ball itself. Notice the person in the background who is detected despite the area being highly blurred and partially obscured.