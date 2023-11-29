# Neural-Style-Transfer
My attempt at transferring stylistic details from one image to another image, generating a new image drawn in the style of the first with content similar to the second.

(To find the project, select the "master" branch instead of the "main" branch).

About the project
I've implemented a Neural Style Transfer using PyTorch on Google Colab. All the image files that I have used or loaded into the notebook are present in the same directory as this file.

Also contained within this file are all the images that were generated as part of the project. They are not saved the way fake.png would be saved, but rather how they appear in the cell output sections. They are named <file_name + style_variable_name>.

To import your own images, please change the paths given to the load() function. The generated image will be called fake.png, created in the same directory as the notebook.

Possible reasons for not-so-spectacular results for the manga and manhwa styles-
1. Too complex
2. Too many borders

Potential improvements
1. Using an autoencoder to reduce noise in the styles
2. Using a GAN (CycleGAN) instead of Neural Style Transfer
3. Using a StyleGAN to improve image quality and definition

Requirements:
torch
torchvision
pillow

To install above libraries, run the command
! pip install <library_name>
In the ipynb file

Running the file:
1. On Google Colab
Simply upload the notebook into Google Colab and run all the cells.

2. On a local machine
Comment out the first cell, then run all cells.

Make sure that your image loading paths are correct.
