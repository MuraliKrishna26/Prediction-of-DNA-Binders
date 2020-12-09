# Prediction-of-DNA-Binders
Identification of DNA-binding proteins is one of the major challenges in the field of genome annotation, as these proteins play a crucial role in gene-regulation. We have developed an model using various machine learning techniques to for predicting DNA-binding domains and proteins.

Kaggle competition link :  https://www.kaggle.com/t/c5c92ff32d324a2884086ccbc83fde67

Dataset given contains strings but machine learning models cannot work with strings. We have to convert string to vectors, this is called feature extraction. We have used four different feature extraction techniques and each technique code file is attached to this repository.

    --- "DNAProtein_Aminoacid20.ipynb" : From each string 20 features are extracted.
    --- "DNAProtein_Dipeptide400.ipynb" : From each string 400 features are extracted.
    --- "DNAProtein_Dipeptide800.ipynb" : From each string 800 features are extracted.
    --- "DNAProtein_Tripeptide8000.ipynb" : From each string 8000 features are extracted.

Please refer the "report.pdf" present in the repository for clear explanation. 



