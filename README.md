
# Deep Regression Tracking with Shrinkage Loss

### Introduction

This is the research code for the ECCV 2018 paper: 

[Xiankai Lu](https://github.com/carrierlxk),  [Chao Ma](https://www.chaoma.info), [Bingbing Ni](https://scholar.google.com/citations?user=eUbmKwYAAAAJ&hl=en), [Xiaokang Yang](http://english.seiee.sjtu.edu.cn/english/detail/842_802.htm), [Ian Reid](https://cs.adelaide.edu.au/~ianr/), and [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/), Deep Regression Tracking with Shrinkage Loss ([paper link](http://faculty.ucmerced.edu/mhyang/papers/eccv2018_rtsl.pdf)), ECCV 2018. 

![](../master/framework.png)

### Abstract
Regression trackers directly learn a mapping from regularly dense samples of target objects to soft labels, which are usually generated by a Gaussian function, to estimate target positions. Due to the potential for fast-tracking and easy implementation, regression trackers have received increasing attention recently. However, state-of-the-art deep regression trackers do not perform as well as discriminative correlation filters (DCFs) trackers. We identify the main bottleneck of training regression networks as extreme foreground-background data imbalance. To balance training data, we propose a novel shrinkage loss to penalize the importance of easy training data.  Additionally, we apply residual connections to fuse multiple convolutional layers as well as their output response maps. Without bells and whistles, the proposed deep regression tracking method performs favorably against state-of-the-art trackers, especially in comparison with DCFs trackers, on five benchmark datasets including OTB-2013, OTB-2015, Temple-128, UAV-123 and VOT-2016.

### Quick Start

1. Compile matcaffe in the caffe-dslt folder

2. Run 'run_DSLT.m' and test the proposed tracker

Note that "vot.m" is the inferface for running tests on the VOT dataset

### Downloads

The tracking results on the OTB dataset are in [BaiduPan](https://pan.baidu.com/s/1zqHDdNer9bnnq8NXCigrEw), Temple 128 dataset are in [BaiduPan](https://pan.baidu.com/s/1P5rYFWUBDCKQ4x_E9YNHgw), VOT-2016 dataset in [BaiduPan](https://pan.baidu.com/s/1VQ34WPVAimHXO0iZRFCm-g). 

### Citation

This work reused partial code from [the FCNT tracker](https://github.com/scott89/FCNT). If you find the code and dataset useful in your research, please consider citing:


    @inproceedings{Lu-ECCV-2018,
        title={Deep Regression Tracking with Shrinkage Loss},
        Author = {Lu, Xiankai and Ma, Chao and Ni, Bingbing and Yang, Xiaokang and Reid, Ian and Yang, Ming-Hsuan},
        booktitle = {European Conference on Computer Vision},
        Year = {2018}
    }


    @inproceedings{ wang2015visual,
         title={Visual Tracking with Fully Convolutional Networks},
           author={Wang, Lijun and Ouyang, Wanli and Wang, Xiaogang and Lu, Huchuan},
           booktitle={IEEE International Conference on Computer Vision (ICCV)},
           year={2015}
        }


### Contents
|  Folder    | description |
| ---|---|

Feedbacks and comments are welcome! Feel free to contact us via [carrierlxk@gmail.com](mailto:carrierlxk@gmail.com) or [chaoma99@gmail.com](mailto:chaoma99@gmail.com).

Enjoy!
