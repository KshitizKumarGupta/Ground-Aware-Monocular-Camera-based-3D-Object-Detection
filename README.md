# Monocular Ground Aware 3D Object Detection:

This repo aims to provide flexible and reproducible  3D object detection on KITTI dataset. I expect scripts starting from the current directory, and treat ./visualDet3D as a package that one could modify and test directly instead of a library. Several useful scripts are provided in the main directory for easy usage.

I believe that visual tasks are interconnected. 
The package uses registry to register datasets, models, processing functions and more, allowing easy inserting of new tasks/models while not interfere with the existing ones.



## Key Features

- **SOTA Performance** State of the art result on visual 3D detection.
- **Modular Design** Modular design for dataset, network and running pipelines.
- **Support Various Task** Compatible with the training and testing of mono/stereo 3D detection and depth prediction.
- **Distributed & Single GPU** Support training with multiple GPUs.
- **Installation-Free Setup** The setup process only build operations and does not require installation to keep the environment clean.
- **Global Path-based IMDB** Do not need data placed inside the folder, convienient for managing data and code separately.



Reference: this repo borrows codes and ideas from [retinanet](https://github.com/yhenon/pytorch-retinanet),
[mmdetection](https://github.com/open-mmlab/mmdetection),
[M3D-RPN](https://github.com/garrickbrazil/M3D-RPN),
[DORN](https://github.com/dontLoveBugs/SupervisedDepthPrediction),
[EdgeNets](https://github.com/sacmehta/EdgeNets),
[det3](https://github.com/pyun-ram/FL3D)


In this repo, the folders named as - "config", "objectDet3D" and "scripts" are the ones created by me.
