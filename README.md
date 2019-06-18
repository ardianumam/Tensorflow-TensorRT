This repository is for my YouTube video series [here](https://www.youtube.com/watch?v=AIGOSz2tFP8&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f), about optimizing deep learning model using TensorRT. We demonstrate optimizing LeNet-like model and YOLOv3 model, and get 3.7x and 1.5x faster for the former and the latter, respectively, compared to the original models. For the details and how to run the code, see the video below.


## List of Videos
1. [Optimizing Tensorflow Model to TensorRT](https://www.youtube.com/watch?v=AIGOSz2tFP8&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f)
2. [Visualizing Before and After TensorRT Optimization](https://www.youtube.com/watch?v=Hum7awcBffY&index=2&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f)
3. [Optimizing Keras Model to TensorRT](https://www.youtube.com/watch?v=ky4mFPewl8Y&index=3&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f)
4. [Train Keras Model Using Your Own Dataset](https://www.youtube.com/watch?v=9IEcI5JZWg8&index=4&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f)
5. [Restore and Use Stored Keras Model to Perform Inference](https://www.youtube.com/watch?v=h6X2THHnQ4s&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f&index=5)
6. [Optimizing YOLOv3 using TensorRT](https://www.youtube.com/watch?v=stBYLsq15lY&index=6&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f)
7. [Another YOLOv3 Detection Result (Native Tensorflow vs TensorRT optimized)](https://www.youtube.com/watch?v=IVUl61p6efU&list=PLkRkKTC6HZMwdtzv3PYJanRtR6ilSCZ4f&index=7)

## Pre-requirement
1. TensorRT: follow the tutorial [here](https://steemit.com/deeplearning/@ardianumam/installing-tensorrt-in-ubuntu-desktop) for Ubuntu dekstop or [here](https://steemit.com/deeplearning/@ardianumam/installing-tensorrt-in-jetson-tx2) for Jetson devices, to install tensorRT

## Library I Use:
1. Tensorflow 1.12 (Dekstop) and Tensorflow 1.11 (Jetson TX2)
2. OpenCV 3.4.5
3. Pillow 5.2.0
4. Numpy 1.15.2
5. Matplotlib 3.0.0


## Environment used in this video series
**Dekstop PC**
1. OS: Ubuntu 16.04 - 64bit
2. GPU: GeForce 1060 6Gb
3. Driver version: 384.130
4. RAM: 16Gb
5. CUDA: 9.0
6. CuDNN: 7
7. TensorRT: 4.1.2
8. Python: 64-bit, version 3.5

**Jetson TX2**
1. OS: Ubuntu 16.04 - 64bit
2. GPU (with RAM shared): 8Gb
3. Driver version: Given along flashing with Jetpack 3.3
4. CUDA: 9.0
5. CuDNN: 7
6. TensorRT: 4.1.3
7. Python: 64-bit, version 3.5

## Dataset
Download (subset of) MNIST dataset [here](https://drive.google.com/file/d/1GOeU5T5EinT98VJsDbV0REyxEdgDwvio/view?usp=sharing), extract and put in folder `dataset`.

## YOLOv3 Frozen Model
Download [here](https://drive.google.com/file/d/1tH6RCYXfsvS_BC2Z_zEd7mu4uMYW4dsr/view?usp=sharing), extract and put in folder `model/YOLOv3` 

## License: The MIT License
```
Copyright 2019 - Ardian Umam

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
