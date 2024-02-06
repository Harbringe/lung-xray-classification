# lung-xray-classification

Welcome to the lung xray classification repository! This Jupyter Notebook focuses on classifying lung xrays of patients either having pneumonia, covid or healthy lungs. The dataset is organized into 3 folders (covid, pneumonia, normal), each containing chest X-ray posteroanterior (PA) images. In total, 6939 samples were used in the experiment, with 2313 samples for each case.

## About

The repository contains a `history.csv` file which contains all the training data per epoch of the model.
The `.ipynb` file contains all the model training and evaluation.

## Getting Started

### Prerequisites

Before running the notebook, ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

### Steps to Run the Notebook
1. Clone this repository to your local machine:

```bash
git clone https://github.com/Harbringe/lung-xray-classification/
```
2. Navigate to the project directory:
```bash
cd lung-xray-classification
```
3. Download the dataset using the provided link and place it in the project directory.

4. Open and run the "lung_Xray_classification.ipynb" notebook using Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook lung_Xray_classification.ipynb
```
Follow the instructions in the notebook to execute each cell.

## Model

The model showed exceptional results and has done very well at classifying the X-rays with 95% accuracy. For the link to the Keras model, please follow this link: [model.keras](https://huggingface.co/Harbringe/lung_xray_classification_model/resolve/main/model.keras).

Link to dataset: [COVID19 Pneumonia Normal Chest Xray PA Database](https://www.kaggle.com/datasets/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset)


Feel free to explore the notebook to understand the modeling process and results. Happy classifying!

