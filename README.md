# CodeAlpha Iris Classification

## Overview
This repository demonstrates a complete machine learning workflow for classifying Iris flower species using the classic Iris dataset. The project is implemented as a Jupyter Notebook and covers data loading, exploration, visualization, model training, and performance evaluation.

## Objectives
- Load and inspect the Iris dataset
- Explore feature distributions and relationships
- Visualize class separation with charts
- Prepare data for supervised learning
- Train and evaluate classification models
- Present the workflow in a reproducible notebook

## Dataset
- `Iris.csv` contains the classic Iris dataset used in this project
- Includes 150 samples with 4 features and 3 species labels
- No missing values are present in the dataset

## Technologies
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Project Structure
```text
CodeAlpha_Iris_Classification/
├── Iris_Classification.ipynb   # Main notebook with the full workflow
├── Iris.csv                    # Dataset used for the project
├── README.md                   # Project overview and instructions
├── requirements.txt            # Python dependencies
└── .gitignore
```

## Notebook Workflow
1. Load and inspect the dataset
2. Clean and preprocess data
3. Visualize feature distributions and species relationships
4. Split data into training and testing sets
5. Train classification models
   - Decision Tree Classifier
   - Random Forest Classifier
6. Evaluate model performance using accuracy, confusion matrix, and classification report

## Installation
Install dependencies from `requirements.txt` if available. Otherwise install the required libraries manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Running the Project
1. Activate your Python environment
2. Launch Jupyter Notebook or Jupyter Lab
   ```bash
   jupyter notebook Iris_Classification.ipynb
   ```
3. Open `Iris_Classification.ipynb`
4. Run the notebook cells in order

## Results
The notebook illustrates how a supervised learning model can distinguish Iris species using sepal and petal measurements. It includes exploratory visualizations and evaluation results such as confusion matrices and classification reports.

## Notes
- This project is a good introduction to exploratory data analysis and classification with scikit-learn.
- For reproducibility, add exact package versions to `requirements.txt`.
