# RobustGAN
coming soon!
# Installation Guide
1. Clone our repo:
```bash
git clone https://github.com/yuetyang/RobustGAN.git
```
2. Create new virtual environment:
```bash
conda create -n venvRobustGAN python=3.8
conda activate venvRobustGAN
```
3. Install our dependencies by running the following command:
```bash
pip install -r requirements.txt
```

# Training
```bash
python train.py --dataroot ./datasets/demo_ct_pet --name robustgan_ct_pet --model robustgan --netG robustgan
```
# Testing
```bash
python test.py --dataroot ./datasets/demo_ct_pet --name robustgan_ct_pet --model robustgan 
```
%# Acknowledgements
%This project is developped on the codebase of [CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix.git). We  appreciate this great work! 
