# Binary Classification of Software Defects (PyTorch)

Main goal of this project: Develop a robust model for predicting software defects based on various variables related to software. The dataset used is synthetic and generated from the Software Defect Prediction dataset, available at www.kaggle.com/datasets/semustafacevik/software-defect-prediction.

The project involves two datasets: training data with 101,763 entries and testing data with 67,842 entries (refer to the /data folder).

Key steps in the project include:

- Exploratory Data Analysis (EDA)
- Feature engineering (skipped, but could enhance the final result)
- Checking absolute correlations
- One-Hot Encoding (OHE) and other categorization techniques
- Preparing a Transformer for Neural Network (NN)
- NN Training
- Generating final predictions
- Validation

The model was validated on the test data, producing the best result of approximately 0.78. A more detailed explanation is provided in the accompanying .ipynb file.

The technical stack used in the project includes Python, pandas, PyTorch, matplotlib, scikit-learn, and numpy.