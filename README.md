# Warp Flow with Pytorch
This repository contains the PyTorch implementation of optical flow warping. The implementation is based on [the TensorFlow implementation](https://github.com/rajat95/Optical-Flow-Warping-Tensorflow).

# Motivation
When reproducing the result of [PWC-Net](https://github.com/NVlabs/PWC-Net), I tried to warp the optical flow back to the first frame, while the warping function in the model provided by the author did not work (maybe it's because I made some stupid mistake on normalization).

# How to Run
Demo data is also leveraged from [the original TensorFlow implementation](https://github.com/rajat95/Optical-Flow-Warping-Tensorflow). 
```
python run.py
```
The recon.png is generated in the `data` folder.
