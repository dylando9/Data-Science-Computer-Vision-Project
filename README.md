# Technological Classification of Disaster Type and Damage Severity
### Created by:</u> Francine Bianca Oca, Kassady Marasigan, Dylan Do
<u>Date of Created:</u> 03/15/2024 <br>
<u>Last updated: </u> 05/10/2024 <br>
<b>Description: <i>This is the main directory for the Technological Classification of Disaster Type and Damage Severity project</i></b>

The directory structure is as follows:

LIST OF SUBDIRECTORIES IN '3039558030_3039556912_3039560279' DIRECTORY:
- **data/**: Contains all the datasets used in this project. The datasets are adapted from the xView2 dataset, which includes high-resolution satellite images of real-world building damage caused by various natural disasters.

- **analysis/**: Includes Jupyter Notebook used for data analysis, feature extraction, model training, and validation.

- **narrative/**: Contains the narrative PDF report of the project, detailing the methodology, experiments, results, and conclusions.

- **figures/**: Contains the figures included in the narrative PDF, which illustrate the data exploration, model performance, and other relevant visualizations.

LIST OF FILES IN THIS DIRECTORY:
- **README.md**: This file


## Project Abstract

The project applies classification techniques to satellite imagery to recognize damage from three types of natural disasters: Midwest Flooding, Socal Fire, and Hurricane Matthew. The model performs two main tasks:
1. **Disaster Type Classification**: Classifying satellite images into one of three disaster types: flood, hurricane, and fire.
2. **Damage Severity Classification**: Assigning damage severity levels to images from Hurricane Matthew into four categories (0-3).

The model achieved a mean accuracy of 0.97349 for disaster type classification and an F1 score of 0.5056 for damage severity recognition. Features used for the model include Sobel edge detection, Gabor filters, Local Binary Patterns (LBP), color intensity information, image dimensions, pixel proportions, histogram of oriented gradients, contour count, segment count, and Euler number.

## Methodology

The methodology involves several steps:
1. **Data Exploration**: Visualizing and understanding the dataset through various plots and statistics.
2. **Feature Extraction**: Extracting meaningful features from images such as edges, textures, colors, and shapes.
3. **Model Training**: Using logistic regression for binary and multinomial classification tasks. The model is trained and validated using K-Fold cross-validation to prevent overfitting.
4. **Evaluation**: Assessing model performance using accuracy and F1 score metrics.

