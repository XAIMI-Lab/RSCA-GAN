# RSCA-GAN
This is a **Tensorflow** implementation of our paper:

<a href="https://ieeexplore.ieee.org/abstract/document/9447721">Guangyuan Li, Jun Lv*, Chengyan Wang. "A Modified Generative Adversarial Network Using Spatial and Channel-Wise Attention for CS-MRI Reconstruction." IEEE Access, 2021.</a>

Environment setting: cuda 8.0 + cudnn 6.0 + tensorflow 1.4 + tensorpack 0.8

Train the model
```bash
python train_RSCA.py --gpu=' ' --imageDir=' ' --labelDir=' ' --maskDir=' ' 
```
Test the model
```bash
python train_RSCA.py --gpu=' ' --imageDir=' ' --labelDir=' ' --maskDir=' ' --sample='result/knee_mask_8x/' --load='train_log/knee_mask_8x/max-validation_PSNR_boost_A.data-00000-of-00001'
```

## Citation
If you find this code is useful in your research, please consider to cite:

```
@article{li2021modified,
  title={A modified generative adversarial network using spatial and channel-wise attention for CS-MRI reconstruction},
  author={Li, Guangyuan and Lv, Jun and Wang, Chengyan},
  journal={IEEE Access},
  volume={9},
  pages={83185--83198},
  year={2021},
  publisher={IEEE}
}
```

