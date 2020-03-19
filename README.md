# Detection of helmets on motorcyclists
Motorcycle accidents have been rapidly growing through the years in many countries. In India more than 37 million people use two wheelers. Therefore, it is necessary to develop a system for automatic detection of helmet wearing for road safety. Therefore, a custom object detection model is created using a Machine learning based algorithm which can detect Motorcycle riders. On the detection of a Helmet rider.

> Its a simple YOLO model to detect and count the number of people wearing helmet in a image. this model can be used to detect the intrusion or to find the people ridding bike without helmet.

Getting Started<br>
Download my weight https://drive.google.com/file/d/1r7AF0OrftGQhNpQmbRy--lWu5VgDJvVl/view?usp=sharing in model_data folder then run

> ```python main.py --input <your_video_path>```<br>

## Dependencies
The code is compatible with Python 2.7 and 3. The following dependencies are needed to run the tracker:

```
NumPy
sklean
OpenCV
Pillow
keras
```
Additionally, feature generation requires TensorFlow-1.14.0.

### My Training Loss

<img src="https://github.com/R-code611/helmet_detection_using_machine_learning/blob/master/doc/loss.svg"  width="600" height="500" align="center"/>

### My Validation Loss

<img src="https://github.com/R-code611/helmet_detection_using_machine_learning/blob/master/doc/val_loss.svg"  width="600" height="500" align="center"/>

## Result

<img src="https://github.com/0816-Radhu/helmet_detection_using_machine_learning/blob/master/doc/out.jpg"  align="center"/>

