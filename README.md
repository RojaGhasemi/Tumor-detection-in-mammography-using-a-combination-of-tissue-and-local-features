# Project Title : Tumor detection in mammography using a combination of texture and local features

## Abstract
This research uses a combination of DWT, local binary pattern (LBP), Zernike moment combination, and gray level co-occurrence matrix (GLCM) for feature extraction in medical imaging. Local binary patterns provide faster and simpler calculations, while DWT decomposes images into different frequency components for detailed analysis. GLCM considers the spatial position of pixels, allowing for more variance in the matrix. Zernike moments are effective for feature extraction in mammogram images due to their rotation-invariant features, robustness to noise, and ability to capture both global and local features. These properties make them suitable for accurate and detailed analysis of mammograms. The extracted features are then entered into K-NN classification. The tests have shown high recognition accuracy, with results on the MIAS and DDSM databases.

## Proposed Method
1- Pre-processing breast images
  •	Convert image2grayscale

  •	Resizing to 250×250

2- Feature extraction using combination of local and texture features

  •	Discrete wavelete transform (DWT)

  •	Local binary pattern (LBP)

  •	Zernike moment

  •	Gray level co-occurrence matrix (GLCM)

3- Feature selection using principal component analysis (PCA)

4- Feature classification using K-nearest neighbour (K-NN)

## Dataset
•	MIAS: (322 images): https://www.kaggle.com/datasets/kmader/mias-mammography  
•	DDSM :  (1000 images) https://www.kaggle.com/datasets/skooch/ddsm-mammography 



## Results
The test data have been evaluated with sensitivity, specificity and accuracy parameters. The results of the tests on MIAS and DDSM database have 84.47% and 82.50% recognition accuracy, respectively.

## How to Use

•	Open run.m file and click run button

•	First click train MIAS dataset button

•	Then click test MIAS dataset

•	First click train DDSM dataset button

•	Then click test DDSM dataset

Finally, you can see the accuracy of test data on MIAS and DDSM datasets. 




## Project History
This project was originally completed in 2011. The commit history has been adjusted to reflect the original dates of the work.
