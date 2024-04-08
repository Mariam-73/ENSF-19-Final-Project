# ENSF619 Final Project: Small Object Detection: Steel Surface Defects

## Authors
- Zahra Arabi, Dept. of Electrical and Software Engineering, zahra.arabinarei@ucalgary.ca
- Mariam Manzoor, Dept. of Electrical and Software Engineering, mariam.manzoor@ucalgary.ca

## Abstract
The significance of identifying surface defects in steel cannot be overstated, as it plays a pivotal role in the industry. 
Traditional inspection methods have fallen short in both accuracy and efficiency. However, advancements in deep learning offer significant opportunities for improvement. 
This project addresses these limitations by focusing on refining the performance of the Faster R-CNN object detection model by integrating it with a Path Aggregation Network (PANet). 
This integration is designed to increase the capability of extracting features, by optimizing the flow of information throughout the feature hierarchy. 
This is achieved by incorporating bottom-up path enhancements, resulting in improving the depth and quality of feature extraction. 
Furthermore, in the post-processing phase, we opt for soft non-max suppression (Soft-NMS) over the conventional non-max suppression (NMS) approach. 
This adjustment leads to notable improvements in the recall and precision rates for various defect classes.
The project aims to optimize results on the GC10–DET dataset, which comprises ten different types of defects at varying scales. 
This dataset poses a significant challenge due to the diversity of defect categories and the number of images. 
In conclusion, the methodologies applied in this project have successfully elevated defect detection performance, achieving a mean average precision (mAP) of 0.765. 
This is a significant improvement over the results obtained with the original Faster R-CNN algorithm. 
Thus, this approach demonstrates remarkable effectiveness in detecting small surface defects in steel, representing a significant advancement in the field.

## Keywords
surface defect detection, object detection, deep learning, faster R-CNN
