# Classification-of-Kidney-CT-Scans
To perform Classification on Kidney CT images to detect Cyst, Tumor and Stone.

Dataset: https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

Model(s):  EfficientNetB3 and a simple CNN.


Model 1: EfficientNetB3 -> https://colab.research.google.com/drive/1IbPfVQe9hwmREoWAp1t_vCK12qFbuZM-?usp=sharing

Model 2: Simple CNN(grayscale) -> https://colab.research.google.com/drive/1yjf2SLNlP2UEGSPJUggnqnOoTVU6qIAd?usp=sharing

Model 3: Simple CNN(RBG) -> https://colab.research.google.com/drive/18X6QIxktF-zDFxTp97-PSSy4pZaLvzCY?usp=sharing

![image](https://user-images.githubusercontent.com/80914541/212461431-0a4ca708-233f-4c18-90f0-7dfaf5072fef.png)




Inferences:

A radiologist’s accuracy of detecting the Kidney Ailments concerned with CT scans alons is 99%. The models presented here can achieve a similar feat with the best model serving an accuracy of 99.7%.

The Averaged Dice Score obtained was 0.99 for the CNN models and 0.97 for the EfficientNet B3 model.

Typically, a clinician requires approx. 5-10 minutes to interpret a Kidney CT scan. The models here can perform the same task within a fraction of a second.

Although the dataset was imbalanced, but due to presence large number of images, the models were trained well. 

Undersampled the dataset to limit a max size of 500, employed the EfficientNet model, the results were the same.

Deemining EfficientNet B3 to be an overkill, trained EfficientNet B0 from scratch. The performance was appalling!!!	

