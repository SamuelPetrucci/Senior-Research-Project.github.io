# Senior-Research-Project: Comparative Analysis of YOLO v8 and YOLO v11 for Weapon Detection

Senior Research Project: Comparative Analysis of YOLO v8 and YOLO v11 for Weapon Detection
## Overview
This project aims to evaluate and compare the performance of two versions of the YOLO (You Only Look Once) object detection algorithm, YOLO v8 and YOLO v11, in identifying weapons within images. The focus is on assessing their accuracy and speed when run on a local machine with limited computational resources and no GPU.

### Objectives
Dataset Training: Utilize a dataset trained with Ultralytics YOLO to identify weapons in photos.
Algorithm Comparison: Compare YOLO v8 and YOLO v11 in terms of:
Accuracy: Measure the precision and recall of each version in detecting weapons.
Speed: Evaluate the inference time for each version on a local machine without GPU support.
Resource Efficiency: Analyze the performance of both versions under constrained computational resources.
### Methodology
Data Preparation:
Collect and preprocess a diverse set of images containing various types of weapons.
Annotate the images to create a labeled dataset suitable for training YOLO models.
### Model Training:
Train YOLO v8 and YOLO v11 models using the prepared dataset.
Fine-tune hyperparameters to optimize model performance.
### Performance Evaluation:
- Test both models on a separate validation set to measure accuracy.
- Record inference times for each model on a local machine without GPU.
### Analysis and Comparison:
Compare the results of YOLO v8 and YOLO v11 in terms of accuracy and speed.
Discuss the trade-offs between the two versions and their suitability for deployment in resource-limited environments.
### Expected Outcomes
A comprehensive comparison of YOLO v8 and YOLO v11, highlighting their strengths and weaknesses.
Insights into the feasibility of deploying advanced object detection models on devices with limited computational power.
Recommendations for future research and potential improvements in weapon detection algorithms.
### Repository Structure
- data/: Contains the training and validation datasets.

- models/: Includes the trained YOLO v8 and YOLO v11 models.

- scripts/: Python scripts for training, testing, and evaluating the models.

- results/: Performance metrics and comparison results.

- docs/: Documentation and analysis reports.

## Getting Started: 
