# Image analysis and pattern recognition
This repository contains multiple resources related to the assignments and the final project of the course "Image analysis and pattern recognition" (taught by Professor J.-P. Thiran), attended in the Spring semester of 2022 at EPFL. The projects have been done in cooperation with Roberto Minini and Roberto Ceraolo.

While the three assignments focus on different aspects of image analysis (see below for more details on the content), the projects uses the complete pipeline to recognize which play cards are present on a table, and how many chips are on the table. More in detail, starting from an image similar to the one presented below:
![Initial image](/Images/IM_1.png)
The procedure we followed to detect and recognize the cards and the chips has been the following:
- Extraction of the corners of the table from the starting image;
- Warping and cutting of the image to obtain a frontal sub-image containing only the table;
- Splitting of the sub-image containing the table in different sub-regions;
- Further splitting of the region of the table containing the five cards in five sub-images containing the individual cards;
- Detection and classification of the chips;
- Classification of the table cards and the player cards.

The following resources are present in the repository:
- [Jupyter notebook for the first assignment](/lab_01_segmentation.ipynb), covering topics related to image segmentation;
- [Jupyter notebook for the second assignment](/lab_02_object_description.ipynb), covering topics related to object description;
- [Jupyter notebook for the third assignment](/lab_03_classification.ipynb), covering topics related to object classification;
- [Folder containing all resources related to the final project](/Final_Project/). In particular, the produced code is available in the [corresponding subfolder](/Final_Project/Code/), while the [final presentation](/Final_Project/Presentation.pdf) introduces in detail all the steps (briefly stated above) which are necessary to detect the cards and the chips starting from the complete image.