# Compressive strength of concrete

## Predict the strength

![Untitled design (4)](concrete.png)

![Untitled design (5)](concrete2.jpg)

- This repository represents **" Compressive Strength of Concrete using Machine Learning techniques "**.
- With the help of this project we can ease the work of **" Constructors based on the some factors "**.
  
## 📝 Description

- In this project I have used  **XGBOOST** as a ML Technique.

## ⏳ Dataset
- Download the dataset :
- https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

## :desktop_computer:	Installation

### :hammer_and_wrench: Requirements
* Python 3.8
* Flask
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Dill

## :gear: Setup
1. Install PyTorch :-
```bash
$ pip3 install torch==1.1.0 torchvision==0.3.0

```
2. Install :-
```bash
$ export PATH=/usr/local/cuda/bin/:$PATH

```
```bash
$ export LD_LIBRARY_PATH=/usr/local/cuda/lib64/:$LD_LIBRARY_PATH

```
```bash
$ pip install cython

```
```bash
$ sudo apt-get install libyaml-dev

```
```bash
$ python setup.py build develop --user

```
```bash
$ python -m pip install Pillow==6.2.1

```
```bash
$ pip install -U PyYAML

```
## 🎯 Inference demo
1. Testing with **Images** ( Put test images in **AlphaPose/examples/demo/** )  :-
```bash
$ python scripts/demo_inference.py --cfg configs/coco/resnet/256x192_res50_lr1e-3_1x.yaml --checkpoint pretrained_models/fast_res50_256x192.pth --indir examples/demo/ --save_img

```
2. Testing with **Video** ( Put test video in **AlphaPose/examples/demo/** )  :-
```bash
$ python scripts/demo_inference.py --cfg configs/coco/resnet/256x192_res50_lr1e-3_1x.yaml --checkpoint pretrained_models/fast_res50_256x192.pth --video examples/demo/3.mp4 --outdir examples/res1 --save_video --gpus 0

```


### :book: Please Go through [Concrete_Compressive_Strength.docx](https://github.com/iNeuron-ai/Pose-with-Action/blob/main/doc/Pose_With_Action_HLD2.docx) for more info.


## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> 
- Atiq Mansoori
