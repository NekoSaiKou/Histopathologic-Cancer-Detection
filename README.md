# Histopathologic-Cancer-Detection
A kaggle topic -- Histopathologic Cancer Detection

Requirement:  
    
    Pandas
    Numpy
    fastai
    matplotlib
    sklearn
    opencv

This is a implementation of a kaggle competition --[Histopathologic Cancer Detection](https://www.kaggle.com/c/histopathologic-cancer-detection/overview)  

For some reson, just a part of data is uesd.  

With the help of fast.ai and built-in model of pytorch, one can reach good performance without a lot of works.  

Resnet34, Resnet50 and Resnext50 are used in this notebook. **Transfer learning**  is a machine learning technique that help me transfer the model trained with ImageNet dataaset to the Histopathologic Cancer image.  

The detailed explanation of what I do is in the notebook.  

Model performance on validation set:

    Precision:  96.7%
    Recall:     94.5%
    Accuracy:   96.4%

Model performance on validation set:

    Precision:  No record
    Recall:     No record
    Accuracy:   96.5%