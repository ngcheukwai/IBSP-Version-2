# IBSP Project Fall detection

Version-2 Download Link:https://drive.google.com/file/d/1NAsc9dNBgw3B4cNQqCDujwiDKeDdxynG/view?usp=sharing

Video is bigger than 25MB So I uploaded to google drive.

```
Different of version 1:
1.Combine SVM and Main(Human pose)
2.Added x3 video for demo
3.Added 3D dataset 
4.Two function to re-format data
```
First download the project. Then,just follow the below guide to setup the environment.

### Requirements

```
Requirements for the lightweight-human-pose-estimation-3d (ForDisplay.py)
1.torch>=1.0
2.onnx>=1.6
3.opencv-python>=3.4
4.numpy>=1.17 (Should include in opencv)

Requirements for the SVM (SVM4.py)
1.sklearn
2.numpy (Should include in opencv)
```

### Installing

```
Step by step to install library on anaconda(lightweight-human-pose-estimation-3d ForDisplay.py)
1.install anaconda 64 bit version and reboot computer
2.Create a new environment e.g. Fall detection
3.Make sure install the latest Nvidia display card driver
4.Open a Terminal(Fall detection environment)
5.Type below command
5.1 "conda install -c anaconda cmake"
5.2 "conda install -c conda-forge opencv"
5.3 "conda install -c pytorch pytorch"
5.4 "conda install -c conda-forge onnx"
5.5 (I think numpy should include in opencv if not type "conda install -c anaconda numpy" to install numpy)
```


```
Step by step to install library on anaconda(SVM SVM4.py)
1.Use above enviroment to open a Terminal(Fall detection environment)
2.Type below command or install package "sklearn"
2.1 "conda install -c anaconda scikit-learn"
2.2 (I think numpy should include in opencv if not type "conda install -c anaconda numpy" to install numpy)
```


## Document explanation:

```
ForCSVOutput.py #Use to generate a csv which store the keypoints coordinate.
ForDisplay.py #Use to showcase the draw of human skeleton.
SVM4.py #Use to training the data and predict.
Fall2dNew.csv #Use to store 2d coordinate of fall case.
Sit2dNew.csv #Use to store 2d coordinate of sit case.
Stand2dNew.csv #Use to store 2d coordinate of stand case.
123.csv #A dataset of 9 image fall case for testing prediction.
video.avi #It is a test video.
human-pose-estimation-3d.pth #Pre-trained model of human-pose-estimation-3d
```
## Main Source:

```
https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch
Main Library:
https://anaconda.org/pytorch/pytorch
https://anaconda.org/conda-forge/onnx
https://anaconda.org/conda-forge/opencv
https://anaconda.org/anaconda/scikit-learn
https://anaconda.org/anaconda/numpy

```
