# Cervical_cancer_screening_with_computer_vision

ABSTRACT:     
Visual Inspection with Acetic Acid (VIA) is a cost-effective and widely used cervical cancer screening method, particularly in underdeveloped and developing regions. With the growing success of computer vision in medical imaging applications, this project aims to enhance VIA screening by integrating Computer Vision and Machine Learning techniques. We evaluate the performance of several deep learning models on cervix images obtained through VIA:   
1. VGG16: 98% AUC
2. ResNet-50: 97% AUC
3. YOLOv9: 93% precision
4. YOLO-NAS (Medium): 91% precision.    
   
In addition to image classification, we used a Random Forest model to analyze demographic, behavioral, and clinical features, identifying key predictors of cervical cancer. An ensemble model trained on these features achieved an accuracy of 94%.
    

   
OBJECTIVES:
1. Automatically classify cervix images captured during VIA screening using deep learning models.
2. Predict cervical cancer risk using patient-level features to support early detection, even in VIA-negative cases.      
Our approach aims to improve the overall accuracy and reliability of cervical cancer screening, going beyond the traditional VIA method.

FULL THESIS:    
Read the complete thesis here: [Link](https://dspace.bracu.ac.bd:8443/xmlui/handle/10361/25092)   
Authors: Rezwan Ahmed, Zulkar Nain, Aziz Ahmed, Kawser Sultana   
Supervisor: Associate Professor Md. Ashraful Alam, PhD    
Affiliation: CVIS Research Lab, BRAC University   

REPOSITORY CONTENT:   
This repository contains the Python code for the best-performing model (VGG16) used for cervix image classification.   

For a complete understanding of the methodology, models, and feature-based analysis, please refer to the full thesis paper linked above.

