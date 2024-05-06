# Minor Project

This repository holds my final year project during my time at the [University](https://www.google.com/) titled *'Deep Learning for Emotion Recognition in Cartoons'*.

#### Abstract

*Emotion Recognition is a field that computers are getting very good at identifying; whether it's through images, video or audio. Emotion Recognition has shown promising improvements when combined with classifiers and Deep Neural Networks showing a validation rate as high as 59% and a recognition rate of 56%.*

*The focus of this dissertation will be on facial based emotion recognition. This consists of detecting facial expressions in images and videos. While the majority of research uses human faces in an attempt to recognise basic emotions, there has been little research on whether the same deep learning techniques can be applied to faces in cartoons.*

*The system implemented in this paper, aims to classify at most three emotions (happiness, anger and surprise) of the 6 basic emotions proposed by psychologists Ekman and Friesen, with an accuracy of <b>80%</b> for the 3 emotions. Showing promise of applications of deep learning and cartoons. This project is an attempt to examine if emotions in cartoons can be detected in the same way that human faces can.*

#### Dataset

The dataset used in this dissertation is a collection of **4,800** *Tom & Jerry* face images. 

#### Requirements

+ [Python 3.10](https://python.org)
+ [OpenCV 3.2+](http://opencv.org/)
+ [TensorFlow 2.0 CPU/GPU (GPU Recommended)](https://tensorflow.org)
+ [Jupyter Notebook (Optional)](http://jupyter.org)

#### Install

```
git clone https://github.com/AbhishekSharma-Tech/emotionRecog.git
cd emotionRecog
pip install -r requirements.txt
```

#### Usage

Download the above dataset, the folder must be named `datasets`. Below you can get started with the tools below.

##### Training / Classification / Visualisation

If you just want to train/classify or visualise the output of the network, use this tool:

```
training: (and show summary or results)
usage: python train-tr.py -t [-v|-s]

classification:
usage: python train-new.py -c image.jpg

visualisation:
usage: python train-new.py -V
```

##### Segmentation

Included in this repo are two [Haar cascade](https://en.m.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework) files trained to detect *Tom & Jerry* faces. Note that if you choose this tool, you have to obtain the *Tom & Jerry* videos yourself.

If you want to segment the *Tom & Jerry* videos into images, use this tool:

```
python segmentation-now.py
```

##### Notebook

If you're the type that likes interactivity and experimentation, both the `segmentation.py` and the `train.py` files have their own Jupyter Notebooks in the `notebooks/` folder. If you're using this, make sure the video and image datasets are in the folder.

#### Special Thanks
I would like to thank the following:

+ Professor 
+ My family and friends
+ My University

#### Citation
Abhishek Sharma, (2023). *Deep Learning for Emotion Recognition in Cartoons*

#### Notes

_Tom & Jerry_ © Warner Bros. Entertainment, Inc


