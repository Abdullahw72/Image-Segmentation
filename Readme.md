# Image Segmentation on Medical Equipment

This project is a basic solution for a image segmentation problem on chemistry lab equipments. This can be extended over other medical or industrial problems. After the segmentation, we can use these images by passing them to further more advances ML models, to solve various classification and detection problems. We have used Fast R-CNN for this purpose, but there are even better approaches available for the task at hand.

## Dataset

The dataset for chemical equipment images can be accessed from:  

- https://zenodo.org/record/4736111#.YsXzLIRByUk


## Installation

To run the code:
- Run the Weight_Train.py to train the model on the images.
- Run the Segmentation_test.py file and change the directory path in "imgPath" variable to your own path, and the name of the torch file which you have trained. 
- There are 1375 images in the test folder. Change the number in "59Eval" written in the directory path to any number between 0 and 1375.

Path Example  
- DS LAB PROJECT\\Project New\\LabPics Chemistry\\Test\\68Eval\\Image.jpg  
- DS LAB PROJECT\\Project New\\LabPics Chemistry\\Test\\100Eval\\Image.jpg  
- DS LAB PROJECT\\Project New\\LabPics Chemistry\\Test\\995Eval\\Image.jpg  


## Libararies Used
- OS
- Numpy
- Pytorch (with CUDA)
- OpenCV2

Refer to the project report attached for more information and displayed results.
