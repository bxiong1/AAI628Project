# AAI628Project Map Generation using Pix2Pix and CycleGAN
## Introduction

This project is working on Google Map generations using Pix2Pix and CycleGAN models. Given the input Satellite Map images, I want to generate the corresponding Google Map images that looks like the one that provided in the dataset.


### Methods

Since this project is a image-to-image translation problem, so using GAN type models, specifically Pix2Pix and CycleGAN are really useful to handle this task. In this project I also compare two models' preformance by:

- Inspect the generated images from Pix2Pix and CycleGAN and compare which generate higher quality images.
- Use Frechet Inception Distance(FID) to measure the distributions between the generated images and the real images and compare the results.

For more information, please review the project report:

* [Download Report](https://github.com/bxiong1/AAI628Project/blob/main/Final%20Report%20for%20Map%20Generation.pdf) - Report

### Dataset

* [Download Dataset](https://drive.google.com/drive/folders/17XsmPkgGLn7pQiSHBSgLHNQa42a_29v2?usp=sharing) - Dataset

Dataset files:
```
Data includes:
- Images are composed of Satellite images and Google Map images
- Train file contains 1096 samples
- Validation file contains 1098 samples
```

### Getting Started

To try out the model and train it on your own, you can simple download the following Notebook files from this page:
```
pix2pixscratch.ipynb
cyclegan.ipynb
```

### Prerequisites

What things you need to install the software and how to install them

```
pip install torch
pip install numpy
pip install pandas
```

All other required modules are written in the Notebook files, you can simple run them on your Notebook.

## Authors

* **Barry Xiong** [bxiong1](https://github.com/bxiong1)
********




## License

This project is licensed under the MIT License
