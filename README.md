# omdena_engie

> Work done for the Omdena-Engie project [Increasing Solar Energy Adoption Through Roof Detection](https://omdena.com/projects/ai-solar/)

This repository consists of Jupyter and Colab Notebooks.  Brief outline:

- [*01_image_preprocessing.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/01_image_preprocessing.ipynb)  
  Crop large satellite image into tiles using `geopandas`, `supermercado`, `rio_cogeo`, and `rio_tiler`.
  
- [*01a_image_preprocessing.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/01a_image_preprocessing.ipynb)  
  Convert all images to RGB images.
  
- [*02_pretrained_ISR_inference.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/02_pretrained_ISR_inference.ipynb)   
  Apply super-resolution to satellite images using pre-trained ESRGAN available at [idealo/image-super-resolution](https://github.com/idealo/image-super-resolution).
  
- [*02a_ISR_training.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/02a_ISR_training.ipynb)
  Training the ESRGAN implementation at [idealo/image-super-resolution](https://github.com/idealo/image-super-resolution).
  
- [03_sr_satellite_datasets.ipynb](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/03_sr_satellite_datasets.ipynb)
  Display and compare satellite images of various resolutions: SpacenetV2 (0.3 m), New Zealand Land Services (0.1 m), xView2 (0.3 m), and Solar-AI's (~ 0.7 m).
  
- [*04_pretrained_ESRGAN-pytorch_inference.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/04_pretrained_ESRGAN-pytorch_inference.ipynb)
  Applying super-resolution to satellite images using pre-trained ESRGAN available at [wonbeomjang/ESRGAN-pytorch](https://github.com/wonbeomjang/ESRGAN-pytorch).
  
- [*05_generate_LR_images_colab.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/05_generate_LR_images_colab.ipynb)
  Generate high resolution and low resolution image pairs for training ESRGAN.
  
- [*06_ESRGAN-pytorch_training_colab.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/06_ESRGAN-pytorch_training_colab.ipynb)
  Training ESRGAN-pytorch on Colab on satellite image data. 
  
- [*07_esrgan_inference_colab.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/07_esrgan_inference_colab.ipynb)
  Inference with ESRGAN trained on satellite images.
  
- [*08_building_segmentation_inference.ipynb*](https://nbviewer.jupyter.org/github/qAp/omdena_engie/blob/master/omdena_engie/08_building_segmentation_inference.ipynb)
  Using pre-trained building segmentation model at [kbrodt/building-segmentation-disaster-resilience](https://github.com/kbrodt/building-segmentation-disaster-resilience) on Solar-AI's images.
  
