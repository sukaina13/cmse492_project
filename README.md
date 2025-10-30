# CMSE 492 Final Project – Porto Seguro Safe Driver Prediction

## Overview
This project focuses on predicting the likelihood that an auto-insurance policyholder will file a claim within the next year.
The goal is to build accurate, interpretable models that help insurance providers better understand risk and reduce financial losses.
To address the severe class imbalance in the dataset, I plan to experiment with ensemble-based learning methods such as Balanced Random Forest and Easy Ensemble.
These approaches will be compared with simpler baseline models to evaluate performance improvements and interpretability.

## Directory Structure

cmse492_project/
├── data/              # Raw and processed datasets  
├── notebooks/         # Exploratory notebooks and analysis scripts  
├── src/               # Preprocessing, model, and evaluation modules  
├── figures/           # Plots and visualizations  
├── docs/              # Supporting documentation  
├── reports/           # LaTeX proposal and final report  
└── README.md


### 1. Clone the repository  
```bash
git clone https://github.com/sukaina13/cmse492_project.git
cd cmse492_project

## Setup Instructions
After cloning, create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
