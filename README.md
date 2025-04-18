# DS4002-Project3: Decade Detective: Dating Images Through Color    
### Group Leader: Ethan Banerjee
### Group 20: Camila Gutierrez, Will Mayer

## (1) Software and Platform
Software type: Python 

*Pandas Package
*Numpy Package
*OS Package
*Pathlib Package
*Torch Package (PyTorch)
*Torchvision Package
*PIL (Pillow) Package
*Seaborn Package
*Matplotlib Package
*Scikit-learn Package
 

Platform: Mac/Windows
## (2) A Map of Documentation
This repository contains the contents necessary to implement our sentiment analysis, which consists of 3 main folders:

DATA FOLDER: 
* The data folder becomes populated when you run the "make data" file in the SCRIPTS FOLDER. It has two terminal commands.   

OUTPUT FOLDER: 
* **[OUTPUT/eda1.png](OUTPUT/eda1.png)**
* **[OUTPUT/eda2.png](OUTPUT/eda2.png)**
* **[OUTPUT/eda3.png](OUTPUT/eda3.png)**
* **[OUTPUT/eda4.png](OUTPUT/eda4.png)**


SCRIPTS FOLDER:
* **[SCRIPTS/eda.ipynb](SCRIPTS/eda.ipynb)**: This script uses raw data to perform exploratory data analysis and generate visualizations. The dataset of historical color photos is categorized by decade and image features like brightness and contrast are extracted. Feature trends are visualized over time. 
* **[SCRIPTS/make_data.ipynb](SCRIPTS/make_data.ipynb)**: This script uses raw data to create the established dataset. Run the following two cells to populate the DATA/ folder with the necessary data for the analysis.
* **[SCRIPTS/analysis.ipynb](SCRIPTS/analysis.ipynb)**: This script uses the established data set to perform analysis and generate visualizations. We use convolutional neural networks (CNNs) to extract spatial and color-based features that define each decade’s photographic style. The model will then be trained using supervised classification techniques, including CNNs and k-nearest neighbors (KNN), to assess how well different approaches can classify images based on their color composition. Our analysis will follow three main steps: model definition, training, and performance evaluation. 

## (3) Result Replication

### In order to replicate the results of our study, you must follow these steps:
If you want to fully recreate our dataset, you can run [SCRIPTS/make_data.ipynb](SCRIPTS/make_data.ipynb).

Recreating our dataset requires the following dependencies:
- pandas
- numpy
- os
- PIL (Pillow)
- torch
- scipy.io
- imageio.v2

To recreate our analysis, run analysis.ipynb.

## (4) References
[1] T. Han et al., “Learning from Streaming Video with Orthogonal Gradients,” Apr. 02, 2025, arXiv: arXiv:2504.01961. doi: 10.48550/arXiv.2504.01961.; H. Wang, F. Liu, J. Chi, and Y. Duan, “VideoScene: Distilling Video Diffusion Model to Generate 3D Scenes in One Step,” Apr. 02, 2025, arXiv: arXiv:2504.01956. doi: 10.48550/arXiv.2504.01956.; W. Wang et al., “Image Difference Grounding with Natural Language,” Apr. 02, 2025, arXiv: arXiv:2504.01952. doi: 10.48550/arXiv.2504.01952. 

[2] P. Messier, “Notes on Dating Photographic Paper (2006),” Issues in the Conservation of Photographs, vol. 3, p. 98, Jan. 2010. 
