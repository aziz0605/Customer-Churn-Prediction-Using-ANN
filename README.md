# Customer Churn Prediction Using ANN

## Project Overview
This project uses an Artificial Neural Network (ANN) to predict whether a customer is likely to leave a service (Churn) or continue using it.

The model is developed using TensorFlow and Keras, with Scikit-learn for data preprocessing and feature scaling.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## Project Workflow
1. Import Required Libraries
2. Data Loading and Cleaning
3. Categorical and Numerical Feature Separation
4. Data Preprocessing
5. Train-Test Split
6. ANN Model Building
7. Model Compilation
8. Model Training
9. Model Evaluation
10. Training and Validation Visualization

## Data Preprocessing
- Handled missing values in the `internet_service` column.
- Separated categorical and numerical columns.
- Used `StandardScaler` for numerical features.
- Used `OneHotEncoder` for categorical features.
- Split the dataset into 80% training and 20% testing data.

## ANN Model Architecture
- Input Layer
- Dense Layer (64 neurons, ReLU activation)
- Dropout Layer (0.3)
- Dense Layer (32 neurons, ReLU activation)
- Output Layer (1 neuron, Sigmoid activation)

## Model Configuration
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 50
- Batch Size: 32

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 85.67% |
| Test Loss | 0.3320 |

## Visualization
The project includes training and validation graphs to monitor:
- Accuracy
- Loss
  <img width="1018" height="393" alt="image" src="https://github.com/user-attachments/assets/1fcbcdda-7e0b-487b-98ae-3b7f1dfbce6b" />


## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Customer-Churn-Prediction-Using-ANN.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
   ```

3. Open the Jupyter Notebook or Google Colab.
4. Make sure the dataset `Customers report.csv` is available.
5. Update the dataset path if necessary.
6. Run all notebook cells.

## Project Structure

```text
Customer-Churn-Prediction-Using-ANN/
│
├── Customer_Churn_Prediction_Using_ANN.ipynb
├── Customers report.csv
└── README.md
```

## Conclusion
This project demonstrates the application of Artificial Neural Networks in solving a binary classification problem. The model predicts customer churn based on customer-related features and achieved 85.67% test accuracy.

## Author
A.ABDUL AZIZ
