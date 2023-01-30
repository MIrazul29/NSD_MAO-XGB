# NSD_MAO-XGB

This repository contains code for the thesis titled "A Modified Aquila Based Optimized XGB Framework For Detecting Probable Seizure In Neonates".

", which has been submitted to Electronics and Communication Engeering Discipline, Khulna University, Khulna. The overall graphical block diagram of our proposed approached is illustrated in Figure below.
  

![image](https://user-images.githubusercontent.com/81968951/215566515-fd1e312d-3ac4-4390-9624-039001581f3a.png)



# Folder description:
###### HGSORF_CSection: this folder contains pretrained file and corresponding codes. User have to run [Csection_final.ipynb ](https://github.com/genos29/HGSORF_CSection/blob/main/HGSORF_CS/Csection_final.ipynb) script to get the result presented in the paper. Note that, [Csection_final.ipynb ](https://github.com/genos29/HGSORF_CSection/blob/main/HGSORF_CS/Csection_final.ipynb) script is developed on Python 3.6 & SkLearn 0.24.1. Two custom made utilis: [Ploting_Utils](https://github.com/genos29/HGSORF_CSection/blob/main/HGSORF_CS/ploting_utils_v1.ipynb) and [Confusion_Matrix](https://github.com/genos29/HGSORF_CSection/blob/main/HGSORF_CS/confusion_matrix_pretty_print.ipynb) are required to run the code. The following dependencies must be installed before running this script. Our proposed [HGSORF](https://github.com/genos29/HGSORF_CSection/blob/main/HGSORF_CS/optimized_RF_model_usingHGSO.rar) model is in RAR format (optimized_RF_model_usingHGSO.rar), users have to unzip it in order to use it.
Dependencies:
```
Numpy
Pandas 
Mealpy
Matplotlib
Seaborn
Pickle
Shap
Lime
Warnings
Pycm
```


 Authors:
 ```
Khondoker Mirazul Mumenin
Md. Abdul Awal
```
For inquires or suggestions please contact:
---
k.mirazulmumenin@gmail.com
md.abdul.awal.uq@gmail.com
nahid.ece.ku@gmail.com

---
