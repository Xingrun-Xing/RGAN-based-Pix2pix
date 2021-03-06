# RGAN-based-Pix2pix

This is the code of my conference paper "Image-to-Image Translation using a Relativistic Generative Adversarial Network " in the 11th International Conference of Digital Image Processing (ICDIP 2019). This code refers to the basic [pix2pix-pytorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) code heavily and thinks for the sharing.<br><br>

We use a relativistic generative adversarial network to implement image domain transformation tasks, for example label-to-photo and photo-to-map.<br>
<img src="https://github.com/Xingrun-Xing/RGAN-based-Pix2pix/blob/master/Figure_3.PNG"  width=50%/><br>

### Label-to-photo task on the Cityscapes dataset
<img src="https://github.com/Xingrun-Xing/RGAN-based-Pix2pix/blob/master/Figure_1.png"  width=100%/><br>

### Photo-to-map task on the Google-maps
<img src="https://github.com/Xingrun-Xing/RGAN-based-Pix2pix/blob/master/Figure_2.png"  width=100%/><br>

# Run

### Requirements: 
* Install [PyTorch](https://pytorch.org/) (tested on release 0.4.0 and 0.4.1).
* Clone [Pix2pix-Pytorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) as backbone training framework.
### Training and Validation:
* Copy [pix2pix_model.py](/pix2pix_model.py), into `pytorch-CycleGAN-and-pix2pix/models/` to exchange the basic GAN model.

* Launch training with [Pix2pix-Pytorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) as backbone training framework.


