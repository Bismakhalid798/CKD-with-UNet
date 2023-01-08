# CKD-with-UNet
Introduction to Project:

  Chronic kidney disease (CKD) refers to any long-term condition which deteriorates the functionality of the kidney in body waste filtration. The disease could be treated if diagnosed timely. Keeping this problem domain in view, the proposed approach includes the adaptive machine learning techniques for chronic kidney disease detection to trace the infected areas and create a base for kidney image analysis. Furthermore, we will process the CT scan images of Kidney to determine the abnormality. Moreover, our technique includes promising opportunities as it can further be modified into a wearable device. Also, it can play a considerable role in a patient's health care and diagnostics.  
  
Dataset: 
  
  We used the publically available KITS 19 Challenge dataset. Dataset is available at this link "https://github.com/neheller/kits19"
Usage:

a) In Fyp_working_version notebook we visualized the data and converted the 3D images to PNG slices and stored them in google drive.
b) training_unet_(1) notebook includes UNET model training on the generated png slices. 
c) In dropout_0_05 notebook dropouts are added in the UNET model.
d) In classification_vgg16(1) notebook the experiment is performed where first the data is passed through a classifier and then the output from the classifier is further passed into UNET for segmentation. 
e) dense_full notebook includes addition of dense layers within the UNET model. 

  
