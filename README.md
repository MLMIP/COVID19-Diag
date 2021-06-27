# COVID19-Diag
The usefulness of COVID19-Diag dataset was confirmed by two senior radiologists at the First Hospital of Changsha in China, who diagnosed and treated a large number of patients during the outbreak of COVID-19, and the First Hospital of Changsha is also the main COVID-19 diagnosis and treatment facility in Hunan Province.

Data Description
----
Our COVID19-Diag dataset consists of 69 CT volumes of COVID-19, 95 CT volumes of normal cases, and 62 CT volumes of bacterial pneumonia from the First Hospital of Changsha.
The CT volumes of all the cases are performed on a CT scanner as SIEMENS or GE MEDICAL SYSTEMS with 5mm of slice thickness and 512×512 of the matrix. We extract 1769, 3824, 1389 two dimensional (2D) CT axial slices from COVID-19, normal cases, and bacterial pneumonia respectively, in which the number of slices selected for each CT scan ranges from 2 to 54. A training set and a test set are randomly divided by cases with a ratio of 7 to 3. The size of the images are set to 1×224×224 to accommodate the input of our model. The statistics of the dataset are shown in Table 1. 

| Item | Class | Training | Testing |
| ----- | ----- | ----- | ----- |
|| COVID-19 | 43 | 18 |
| Cases | Normal | 67 | 28 |
|| Bacterial Pneumonia | 48 | 21 |
|| COVID-19 | 1256 | 513 |
| Images | Normal | 2674 | 1150 |
|| Bacterial Pneumonia | 980 | 409 |


The dataset details are described in this article: Deep Supervised Learning Using Self-Adaptive Auxiliary Loss for COVID-19 Diagnosis from Imbalanced CT Images. This dataset is public, if you want to use it for related research, please contact the email: kaihu@xtu.edu.cn to sign the relevant agreement to obtain.

If you find this dataset useful, please cite:

[1] Hu K, Huang Y, Huang W, et al. Deep supervised learning using self-adaptive auxiliary loss for COVID-19 diagnosis from imbalanced CT images[J]. Neurocomputing, 2021, 458: 232-245.

OR

@article{HU2021232,  
  title = {Deep supervised learning using self-adaptive auxiliary loss for COVID-19 diagnosis from imbalanced CT images},  
  author = {Kai Hu and Yingjie Huang and Wei Huang and Hui Tan and Zhineng Chen and Zheng Zhong and Xuanya Li and Yuan Zhang and Xieping Gao},  
  journal = {Neurocomputing},  
  volume = {458},  
  pages = {232-245},  
  year = {2021}  
}
