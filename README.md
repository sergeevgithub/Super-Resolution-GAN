# Super-Resolution-GAN

## Final project for AI CS362 course.

__1. Description__

Image Super-Resolution is a machine learning process used to make images
clearer and more detailed by increasing their resolution. The aim is to keep
the original content and details intact. The outcome is a sharper version
of the original image. The main goal of this project was to delve into the application of GANs 
for this task, and as a result implement working solution based on the paper https://arxiv.org/pdf/1609.04802v5.

__2. Dataset__

DIV2K-x2 dataset (https://data.vision.ee.ethz.ch/cvl/DIV2K/).

__3. Training process__

* Model was trained on Kaggle with GPU P100

* Generator warmup: 150 epoch with lr = 1e-4

* Training: 11250 update iterations with lr = 1e-4

__4. Results__

   <p align="center"><img src="assets/result.PNG" width="1000"\></p>
