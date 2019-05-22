# IKT590
# Instructions 
Download the dataset the from here: https://www.dropbox.com/home?preview=Food11_256.zip

or Download the original dataset from here: https://mmspg.epfl.ch/downloads/food-image-datasets/

and resize the images by using "extract_zipfile.ipynb" and put the datestamps on 
resized images by using "datestamps.ipynb"
-----------------------------------------------------------------------------------------------------------------------
# About this repository 

Title: On the use of Denoising Autoencoders and Deep Convolutional 
Adversarial Networks for Automated Removal of Date Stamps

About: This is the master thesis project conducted by Nicolas Anderson, Mikael Paavola and 
Johnny Sognnes at the university of Agder, Norway 
between Jan 2019 - May 2019

python 3 
Keras based project 
-----------------------------------------------------------------------------------------------------------------------
# Terms  
BCE = Binary Cross Entropy loss function 
DAE = Denoising Autoencoder 
DCGAN = Deep Convolutional General Adversarial Net 
MSE = Mean Squared Error loss function 
MAE = Mean Absolute Error loss function  

-----------------------------------------------------------------------------------------------------------------------
# Acknowledgement 
The code for training DAE network is based on https://github.com/shibuiwilliam/Keras_Autoencoder/blob/master/Cifar_Conv_AutoEncoder.ipynb

The code of training DCGAN network is based on https://github.com/utkd/gans/blob/master/cifar10dcgan.ipynb

-----------------------------------------------------------------------------------------------------------------------
# Information  
Experiment 1: Denoising Autoencoder that includes 6 tests. 
Test 1, 2, 4: overcomplete DAE with different convolution filters that use BCE 
Test 3: undercomplete DAE that use BCE 
Test 5. overcomplete DAE with MSE 
Test 6: overcomplete DAE with MAE 
Experiment 2: DCGAN experiment with date stamp 
Experiment 3: DCGAN experiment without date stamp 
Experiment 4: DAE - Discriminator with date stamp 



