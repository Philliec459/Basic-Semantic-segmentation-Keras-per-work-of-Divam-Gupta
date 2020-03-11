# Image-Segmentation-using-Keras-Segmentation-per-the-work-of-Divam-Gupta
This repository initially came from Divam Gupta's GitHub repository on Image Segmentation using Keras:

https://github.com/divamgupta/image-segmentation-keras

This repository is based on studying Divam Gupta's GitHub repository, blog and other written materials that we have found online. This is great work and a real resource to a novice such as myself. we will be creating a few repositories using our interpretation of how this all might be implemented. We might be wrong, so any constructive criticism is welcome.

This first repository will be based on using Divamgupta's pre-trained example shown in his Readme file. This is the original photo that we are working from:

![Image](1_input.jpg)

We use the pre-trained code to create segmentation items from this photo using load_pretrain_and_create_image.py driven from an xterm. 

![Image](bed_out.png)

In this implementation we interactively select the pixel value associated with a particular segment in the photograph that we are trying to isolate. The python program is interactive_plots_with_box.py. 

We are working with a bedroom picture under the sample_images subdirectory (1_input.jpg). After discriminating all of the major features in the photo as shown above, we then isolate a particular item in the picture (bed), and create a subsequent image showing just that feature with a green rectangle around it. 

![Image](bed_labels_box.png)

We are working in Ubuntu and each python program is driven from an xterm command line using 'python xxxx.py' as the command. 

A second repository is availale here that uses kMean clusters for image segmentation as presented by Vidhya.

Our primary goal is to categorize the different types of grains observed in clastic petrographic thin sections. This is work in progress. Our goal is to estimate the Petrophysical Rock Types and Petrophysical properties from clastic Thin Section photomicrographs.


