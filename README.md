# RobustGAN
## Installation Guide
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
## Training
1. Prepare datasets
   coming soon!
3. Start training
```bash
python train.py --dataroot ./datasets/demo_ct_pet --name robustgan_ct_pet --model robustgan --netG robustgan
```
## Testing
```bash
python test.py --dataroot ./datasets/demo_ct_pet --name robustgan_ct_pet --model robustgan --netG robustgan
```
## Acknowledgements
This project is developped on the codebase of [CycleGAN-and-Pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix.git). We  appreciate this great work! 
## Citation
If you find this codebase useful for your research, please use the following entry.
```BibTeX
@article{yang2025cross,
  title={Cross-Modal Medical Image Generation from MRI to PET Using Robust Generative Adversarial Network},
  author={Yang, Yueteng and Li, Bing and Cao, Wenming and Chen, Xuemei and Li, Weikai},
  journal={Expert Systems with Applications},
  pages={129287},
  year={2025},
  publisher={Elsevier}
}
```
