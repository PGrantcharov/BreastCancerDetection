# Breast Cancer Detection
Using image recognition to identify cancer regions in lymph node cross sections (from CAMELYON dataset).
![Alt text](Images/positives.png?raw=true "Positives")
![Alt text](Images/heatmap.png?raw=true "Heatmap")

## Files
`FullPreprocessing.ipynb` contains all preprocessing code
`MultiImage.ipynb` contains model development code
`Results.ipynb` contains all preprocessing code
`test_prediction.csv` contains all predictions on test sections using just the deep learning model
`lr_prediction.ipynb` contains all predictions on test set using the deep learning model AND the logistic regression add-on

## Overview
![Alt text](Images/overview.png?raw=true "Overview")

## Preprocessing
![Alt text](Images/window.png?raw=true "Window")
![Alt text](Images/align.png?raw=true "Align")
![Alt text](Images/label.png?raw=true "Label")
![Alt text](Images/remove_empty.png?raw=true "Remove Empty")
![Alt text](Images/augment.png?raw=true "Augment")

## Modeling
![Alt text](Images/architecture.png?raw=true "Architecture")
![Alt text](Images/add_on.png?raw=true "Add-On")
![Alt text](Images/training.png?raw=true "Training")

## Results
![Alt text](Images/metrics.png?raw=true "Metrics")
![Alt text](Images/heatmap1.png?raw=true "Heatmap")
![Alt text](Images/heatmap2.png?raw=true "Heatmap")
