# LBSNet: Lightweight Joint Boundary Detection and Semantic Segmentation for Transparent and Reflective Objects

## The paper is currently under review.

![图片2](https://github.com/user-attachments/assets/d3e99136-6386-4543-8afb-0eff28780ea8)

## Requirements

The code has been tested under

- Ubuntu 20.04 + NVIDIA GeForce RTX 3060 (CUDA 11.1)
- PyTorch 1.9.0

## Environment Setup
Setup anaconda environment
```
$ conda create --name lbsnet python=3.8 -y
$ conda activate lbsnet
$ conda install pytorch torchvision -c pytorch
$ pip install -U openmim
$ mim install mmengine
$ mim install "mmcv>=2.0.0"
$ git clone -b main https://github.com/meiguiz/LBSNet.git
$ cd LBSNet
$ pip install -v -e .
```

### Experiments

---
The video of robotic experiments can be found at [this](https://youtu.be/dNT9odmOBgw).


![图片21](https://github.com/user-attachments/assets/1192b9d2-eeb2-4429-8e37-2364bdc6e65c)

---

### Dataset Preparation
- **ClearGrasp-Real**: See [ClearGrasp-Real Dataset used in this project](https://drive.google.com/drive/folders/1FeiipaFirh2Fi20rSTAUJraqqIKqGlOy?usp=drive_link);
