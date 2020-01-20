# Image-Segmentation-Kaggle-Carvana-challenge
Kaggle Carvana Image Segmentation challenge

## Problem Statement
Car Company 'Carvana' request to design a model to eliminate the background from thieir car images. 
Purpose:
1. Reduce the cost of requesting large number of photoshop designers to do cropping and editing 
2. Enabling them to showcase to their customers a '360' view of the cars online.

## Dataset
The Dataset is releatively cleaned. There are minor difference in the way the mask for wheel component for the vechicles are done.

## U-net model


## Loss Function 
As this is a image segmentation problem, the DICE Coefficient is adopted.

## Overall Approach
1. Import Libraries
2. Image Processing (Resizing if required)
3. Run Length Encoding 
3. Loss Lunction (Dice Coefficient)
4. Build U-net Model/ ResNet Model -> Evaluation
5. Conclusion

## Reference
1. Paper  : U-Net: Convolutional Networks for Biomedical Image Segmentation
2. Paper  : Mask R-CNN
3. Github : https://github.com/sainathadapa/kaggle-carvana-image-masking-challenge
4. Github : https://github.com/Walker17/carvana-car-segmentation
5. 'RLE'  : https://www.kaggle.com/stainsby/fast-tested-rle


