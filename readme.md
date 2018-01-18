﻿# TOC
- [Use Cases](https://github.com/lankastersky/neuromantic#use-cases)
  - [Distributed Neural Networks](https://github.com/lankastersky/neuromantic#distributed-neural-networks)
  - [Go game](https://github.com/lankastersky/neuromantic#go-game)
  - [Gesture Recognition](https://github.com/lankastersky/neuromantic#gesture-recognition)
  - [Image Recognition](https://github.com/lankastersky/neuromantic#image-recognition)
  - [Neural Style Transfer](https://github.com/lankastersky/neuromantic#neural-style-transfer)
  - [Sound recognition](https://github.com/lankastersky/neuromantic#sound-recognition)
- [Tools](https://github.com/lankastersky/neuromantic#tools)
  - [Google Cloud AutoML](https://github.com/lankastersky/neuromantic#google-cloud-automl)
  - [Google Mobile Vision](https://github.com/lankastersky/neuromantic#google-mobile-vision)
  - [Playgrounds](https://github.com/lankastersky/neuromantic#playgrounds)
- [Books](https://github.com/lankastersky/neuromantic#books)
- [Articles](https://github.com/lankastersky/neuromantic#articles)
- [MOOC](https://github.com/lankastersky/neuromantic#mooc)

# Use Cases

## Distributed Neural Networks
- [Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer by Jeff Dean et al](https://arxiv.org/abs/1701.06538)
- [PathNet: Evolution Channels Gradient Descent in Super Neural Networks by deepmind](https://deepmind.com/research/publications/pathnet-evolution-channels-gradient-descent-super-neural-networks/)
- [Distilling the Knowledge in a Neural Network by Geoffrey Hinton, 2015](https://arxiv.org/abs/1503.02531)
  - trains a model to mimic the behavior of a pretrained model so it can work independently of the pretrained model
  - can train the smaller model with unlabeled examples
  - not all target classes need to be represented in the distillation training set
  - reduces the need for regularization

## Go game
- [Mastering the game of Go without human knowledge by David Silver et al, 2017](https://www.gwern.net/docs/rl/2017-silver.pdf)

## Gesture Recognition

### Using wearable sensors (phones, watches etc.)

Articles
- [Physical Human Activity Recognition Using Wearable Sensors by Ferhat Attal et al, 2015](http://www.mdpi.com/1424-8220/15/12/29858)
- [Activity Recognition with Smartphone Sensors by Xing Su et al, 2014](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6838194&tag=1)
- [Run or Walk : Detecting Motion Activity Type with Machine Learning and Core ML](https://towardsdatascience.com/run-or-walk-detecting-user-activity-with-machine-learning-and-core-ml-part-1-9658c0dcdd90)
- Android [DetectedActivity class](https://developers.google.com/android/reference/com/google/android/gms/location/DetectedActivity)
- Android [ActivityRecognitionApi](https://developers.google.com/android/reference/com/google/android/gms/location/ActivityRecognitionApi)

Apps
- [Exercise Tracker: Wear Fitness](https://play.google.com/store/apps/details?id=vimo.co.seven)
- [Google Fit - Fitness Tracking](https://play.google.com/store/apps/details?id=com.google.android.apps.fitness)

Code repositories
- https://github.com/droiddeveloper1/android-wear-gestures-recognition
- https://github.com/drejkim/AndroidWearMotionSensors

## Image Recognition
- [TensorFlow-Slim image classification model library](https://github.com/tensorflow/models/tree/master/research/slim)
- [Rethinking the Inception Architecture for Computer Vision by Christian Szegedy et al, 2015](https://arxiv.org/abs/1512.00567)
- [Inception in TensorFlow](https://github.com/tensorflow/models/tree/master/research/inception) - 1.4M images and 1000 classes
- [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications by Andrew G. Howard et al, 2017](https://arxiv.org/abs/1704.04861)
- [ImageNet](http://image-net.org/)
- [Xception: Deep Learning with Depthwise Separable Convolutions by François Chollet, 2017](https://arxiv.org/abs/1610.02357)

## Neural Style Transfer
- [Deep Learning & Art: Neural Style Transfer – An Implementation with Tensorflow in Python](https://www.datasciencecentral.com/profiles/blogs/deep-learning-amp-art-neural-style-transfer-an-implementation)

## Sound recognition

Annotated Datasets
- [The VU sound corpus](https://github.com/CrowdTruth/vu-sound-corpus) - based on https://freesound.org/ database
  - See article [The VU Sound Corpus by Emiel van Miltenburg et al](http://www.lrec-conf.org/proceedings/lrec2016/pdf/206_Paper.pdf)
- [AudioSet](https://research.google.com/audioset/) - consists of an expanding ontology of 632 audio event classes and a collection of 2,084,320 human-labeled 10-second sound clips drawn from YouTube videos
- [How do I listen for a sound that matches a pre-recorded sound?](https://arduino.stackexchange.com/questions/8781/how-do-i-listen-for-a-sound-that-matches-a-pre-recorded-sound)
- The Sound Sensor Alert App [sentector](http://sentector.com/)

# Tools

## [Google Cloud AutoML](https://cloud.google.com/automl/)

Pros:
- let users train their own custom machine learning algorithms from scratch, without having to write a single line of code
- uses Transfer Learning (the more data and customers, the better results)
- is fully integrated with other Google Cloud services (Google Cloud Storage to store data, use Cloud ML or Vision API to customize the model etc.)

Cons:
- limited to image recognition (2018-Q1)
- doesn't allow to download a trained model

## (Google Mobile Vision)[https://developers.google.com/vision/]

Pros:
- Detect Faces (finds facial landmarks such as the eyes, nose, and mouth; doesn't identifies a person)
- Scan barcodes
- Recognize Text

Cons:

## Playgrounds
- [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)

# Books

# Articles

# MOOC

