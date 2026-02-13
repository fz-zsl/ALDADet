<p align="center">
  <h1 align="center">ALDADet: When Active Learning and Data Augmentation Meet at Object Detection</h1>
  <p align="center">
    <a href="https://github.com/fz-zsl">Shengli Zhou (12212232)</a>, <a href="https://github.com/Jaredanwolfgang">Yicheng Xiao (12210414)</a>
    <br></br>
    <img src="https://img.shields.io/badge/SUSTech-CS329-blue">
    <img src="https://img.shields.io/badge/24_Fall-Project-green">
    <img src="https://img.shields.io/badge/Rank-1-orange">
  </p>
</p>

# Implementation Details

The dataset we use is downloaded from [here](https://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d). We then use [kitti2coco](https://github.com/kouyuanbo/kitti2coco) to convert the dataset to COCO format.

The original model is [RT-DETRv2](https://github.com/lyuwenyu/RT-DETR/tree/main/rtdetrv2_pytorch), and we only save the `rtdetrv2_pytorch` folder in this repository.
