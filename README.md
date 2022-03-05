# RSCA-GAN

Environment setting: cuda 8.0 + cudnn 6.0 + tensorflow 1.4 + tensorpack 0.8

Train the model
```bash
python train_RSCA.py --gpu=' ' --imageDir=' ' --labelDir=' ' --maskDir=' ' 
```
Test the model
```bash
python train_RSCA.py --gpu=' ' --imageDir=' ' --labelDir=' ' --maskDir=' ' --sample='result/knee_mask_8x/' --load='train_log/knee_mask_8x/max-validation_PSNR_boost_A.data-00000-of-00001'
```
Paper: 

A Modified Generative Adversarial Network Using Spatial and Channel-Wise Attention for CS-MRI Reconstruction https://ieeexplore.ieee.org/abstract/document/9447721

