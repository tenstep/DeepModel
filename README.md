# Model-based Deep Hand Pose Estimation
This repository is the released code of our IJCAI 2016 paper for estimating hand pose from depth image.

Contact: zhouxy13@fudan.edu.cn

## Requirements
- Caffe
- Python with opencv and h5py

## Installation
- Download [caffe](http://caffe.berkeleyvision.org/) 
- Copy path.config.example to path.config and set the caffe root path
- Copy ./libs/include to caffe_root/include and ./libs/src to caffe_root/src
- Compile caffe

## Test
- Run demo.py in ./testing
 
## Train
Coming soon.

## Citation

Please cite DeepModel in your publication if it helps your research:

    @inproceedings{zhou2016model,
        author = {Xingyi Zhou and Qingfu Wan and Wei Zhang and Xiangyang Xue and Yichen Wei},
        booktitle = {IJCAI},
        title = {Model-based Deep Hand Pose Estimation},
        year = {2016}
    }