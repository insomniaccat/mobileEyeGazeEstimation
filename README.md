# Mobile Eye Gaze Estimation with Deep Learning

In the final project for the "Introduction to Deep Learning" class at RPI (Spring 2017), I have trained a convolutional neural network to estimate the eye gaze of a person as they look at their mobile device. Eye gaze estimation refers to determining an accurate prediction of the direction and/or specific position of where a person is looking at, on a phone/tablet screen. The Input to this model is the face-image of a person as captured by the front-facing camera on their mobile device; and the output is the 2D position (x, y) on the screen’s surface.

The complete report can be found here https://drive.google.com/open?id=1XsdTIR8YkK_Hrjstsj0AV8ddmR13CzNh 

The original dataset comes from the GazeCapture project: http://gazecapture.csail.mit.edu/

Due to limitations in computing power, in an academic setting, our data set consists 48000 training
samples and 5000 validation samples. Each sample has 3 images and a mask. There are, images of (1)
the left eye, (2)the right eye and (3) the face. Each of the 3 images (in each sample) has 3 channels
(RGB) and dimensions, 64x64. Also provided, is a 25x25 face-mask that is a binary grid input that
indicates the location and size of the head within a frame.

The data file can be downloaded here:

https://drive.google.com/open?id=1iDh3bLM9Nc_Nh_k6xeZLk19uz8zRboaN


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

For this project, you need to have python 3.5 and the tensorflow python library v1.4 installed. A good link for setting up your machine can be found here for Ubuntu 16.04:

https://www.pyimagesearch.com/2017/09/27/setting-up-ubuntu-16-04-cuda-gpu-for-deep-learning-with-python/

You would also need the numpy and matplotlib python libraries to run this project. 

## Running the code

By default the data file should be in the same directory as the python script. Then, you could run it using the following command:

```
python eyeGaze.py
```

## Authors

* **Usama Munir Sheikh** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Acknowledgments

* The code is based on lecture notes from Dr Qiang Ji's intro to deep learning class at RPI

