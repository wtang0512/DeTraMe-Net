# Deep Transform and Metric Learning Network (DeTraMe-Net)
This repository contains the demo and Pytorch codes for our paper: "[Deep Transform and Metric Learning Network: Wedding Deep Dictionary Learning and Neural Networks]()" by [Wen Tang](https://www.researchgate.net/profile/Wen_Tang24), Emilie Chouzenoux, Jean-Christophe Pesquet, and Hamid Krim. The Supplementary Material can be found in the [here]().


## Introduction
<p align="center"><img width="40%" src="./imgs/param.jpg"></p>

## Requirements
Python 3.7.4, Pytorch 1.0.0

## How to run
After you have cloned the repository, you can train each dataset of either cifar10, cifar100, SVHN by running the script below.
```bash
python main.py --net_type ['DeTraMe_Plainnet'/'DeTraMe_Resnet'] --depth 8 --widen 1 --steps 2 --dataset ['cifar10'/'cifar100'/'SVHN'] --lr 0.1 --num_epochs 200
```

## Contacts
email: wtang6@ncsu.edu
