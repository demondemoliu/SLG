
##  Introduction

This repository contains the PyTorch implementation of:

Adaptive cervical cell segmentation based on local and global dependence

##  Requirements

* torch
* torchvision 
* tqdm
* opencv
* scipy
* skimage
* PIL
* numpy

##  Usage

####  1. Training

```bash
python train.py  --mode train  --dataset CX22  
--train_data_dir /path-to-train_data  --valid_data_dir  /path-to-valid_data
```



####  2. Inference

```bash
python test.py  --mode test  --load_ckpt checkpoint 
--dataset CX22    --test_data_dir  /path-to-test_data
```



##  Citation

It will be provided soon:

@ARTICLE{
}





