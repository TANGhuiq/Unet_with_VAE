# Unet_with_VAE

## Overview
Unet_with_VAE is a deep learning framework that integrates U-Net, a convolutional neural network for image segmentation, with Variational Autoencoders (VAEs) to enhance generalization through effective feature extraction and data augmentation. This project aims to improve the accuracy and robustness of medical image segmentation tasks, particularly focusing on echocardiographic images.

## Features
- **U-Net Architecture**: Utilizes the U-Net model for precise segmentation of medical images.
- **Variational Autoencoder**: Employs VAE for generating synthetic data that mimics the distribution of training data, thereby enhancing model robustness against overfitting.
- **Cross-device Compatibility**: Tests the model's effectiveness across different medical imaging devices.

## Prerequisites
Before you begin, ensure you have met the following TF2.10-cuda.yml:
name: TF2.10-cuda
channels:
  - conda-forge
  - defaults
dependencies:
  - python=3.9
  - pip
  - matplotlib
  - cudnn
  - cudatoolkit
  - pip:
    - tensorflow==2.10
    - tensorflow-addons[tensorflow]
    - tensorflow-io
    - tensorboard
    - keras==2.10
    - tqdm
    - pandas
    - pillow
    - simpleitk
    - itk
    - medpy
    - scikit-learn
    - scikit-image
    - jupyterlab
    - nibabel
    - opencv-python
    - opencv-contrib-python
    - h5py
    - gpustat
    - spyder-kernels==0.*

        
## Installation
To install Unet_with_VAE, follow these steps:

```bash
git clone https://github.com/TANGhuiq/Unet_with_VAE.git
```

## Contributors
Thanks to the following people who have contributed to this project:
- [@TANGhuiq](https://github.com/TANGhuiq) (The original creator)

## Contact
If you want to contact me you can reach me at <tanghuiqin2023@163.com>.

## License
This project uses the following license: [MIT](https://opensource.org/licenses/MIT).
