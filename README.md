# elvenj-dog-breed-classifier
Udacity Project - Dog Breed Classifier Image classification project using pretrained CNN models (ResNet, AlexNet, VGG) to identify dog breeds and distinguish dogs from non-dogs. Implements batch processing, results analysis, and model performance comparison.

# Dog Breed Classifier

## Description

This project classifies dog breeds using pre-trained CNN models (ResNet, AlexNet, VGG) to identify breeds and distinguish dogs from non-dogs. Developed as part of Udacity's Future AWS AI Scientist program, it implements batch processing, result analysis, and model performance comparison.

## Table of Contents

- [Description](#description)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Results](#results)
- [Credits and Acknowledgments](#credits-and-acknowledgments)

## Project Structure

- `/pet_images/` – image dataset used for training and classification  
- `classify_images.py` – main script for image classification  
- `get_pet_labels.py` – function to extract labels from images  
- `adjust_results4_isadog.py` – helps adjust classification results  
- `calculates_results_stats.py` – calculates model evaluation metrics  
- `final_results_*.txt` – final results of AlexNet, ResNet, and VGG models  
- Other supporting scripts and tests

## Prerequisites

- Python 3.x  
- Libraries: torchvision, torch, numpy, matplotlib, among others  
(Install with `pip install -r requirements.txt` if available)

## How to Run

1. Clone the repository:  
   `git clone https://github.com/elvenj/elvenj-dog-breed-classifier.git`  
2. Navigate to the project directory:  
   `cd elvenj-dog-breed-classifier`  
3. Run the main classification script:  
   `python classify_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt`  
4. Check the textual results generated in the `final_results_*.txt` files

## Results

The files `final_results_alexnet.txt`, `final_results_resnet.txt` and `final_results_vgg.txt` contain accuracy metrics and analysis of breed classification and dog vs. non-dog distinction for each tested model. They show the comparative performance of the models used.

## Credits and Acknowledgments

This project was developed by Elven Jr as part of Udacity's Future AWS AI Scientist program.  
Special thanks to the Udacity instructors and the AWS AI & ML Scholars community for their support and resources.
