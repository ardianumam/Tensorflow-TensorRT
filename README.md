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
1. TensorRT: follow the tutorial [here](https://medium.com/@ardianumam/installing-tensorrt-in-ubuntu-dekstop-1c7307e1dcf6) for Ubuntu dekstop or [here](https://medium.com/@ardianumam/installing-tensorrt-in-jetson-tx2-8d130c4438f5) for Jetson devices, to install tensorRT

## Library I Use:
1. Tensorflow 1.12
2. OpenCV 3.4.5
3. Pillow 5.2.0
4. Numpy 1.15.2
5. Matplotlib 3.0.0

## Dataset
Download (subset of) MNIST dataset [here](https://drive.google.com/file/d/1GOeU5T5EinT98VJsDbV0REyxEdgDwvio/view?usp=sharing), extract and put in folder `dataset`.

## YOLOv3 Frozen Model
Download [here](https://drive.google.com/file/d/1tH6RCYXfsvS_BC2Z_zEd7mu4uMYW4dsr/view?usp=sharing), extract and put in folder `model/YOLOv3` 
