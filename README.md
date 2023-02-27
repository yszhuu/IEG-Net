# IER-Net

This is the implementation of the paper **IER-Net: Information Entropy Refinement Network for Accurate Stereo Matching

# How to use

## Environment
* python 3.6
* Pytorch >= 0.4.1

## Data Preparation

## Training
**Scene Flow Datasets**

run the script `./scripts/sceneflow.sh` to train on Scene Flow datsets. Please update `DATAPATH` in the bash file as your training data path.

**KITTI 2012 / 2015**

run the script `./scripts/kitti12.sh` and `./scripts/kitti15.sh` to finetune on the KITTI 12/15 dataset. Please update `DATAPATH` and `--loadckpt` as your training data path and pretrained SceneFlow checkpoint file.

## Evaluation
run the script `./scripts/kitti12_save.sh` and `./scripts/kitti15_save.sh` to save png predictions on the test set of the KITTI datasets to the folder `./predictions`.

## Pretrained Models
[Scene Flow](https://drive.google.com/file/d/1qiOTocPfLaK9effrLmBadqNtBKT4QX4S/view?usp=sharing)
[KITTI 2012/2015](https://drive.google.com/file/d/1fOw2W7CSEzvSKzBAEIIeftxw6CuvH9Hl/view?usp=sharing)
