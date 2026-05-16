# Part 1: Neural Network Fundamentals and Training Behavior Analysis

## Customer Churn Prediction Using Neural Networks

### Objective
The objective of this project is to build and analyze a feed-forward neural network model for predicting customer churn using structured customer data.

---

## Dataset Information

Dataset Used:
- customer_churn_nn.csv

Target Variable:
- churn
    - 1 = Customer churned
    - 0 = Customer retained

The dataset contains both categorical and numerical customer-related features.

---

## Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Project Workflow

### 1. Dataset Understanding
- Dataset exploration
- Shape analysis
- Data type inspection
- Missing value analysis
- Statistical summary
- Target distribution visualization

### 2. Data Preprocessing
- Removing unnecessary columns
- Encoding categorical features
- Feature scaling using StandardScaler
- Train-test split

### 3. Neural Network Model Building
- Feed-forward neural network creation
- Hidden layers with ReLU activation
- Sigmoid output layer
- Adam optimizer
- Binary crossentropy loss function

### 4. Model Training and Evaluation
- Model training using training dataset
- Validation performance analysis
- Testing accuracy and loss evaluation
- Confusion matrix generation
- Classification report generation

### 5. Hyperparameter Experimentation
Different configurations were tested by changing:
- Number of hidden layers
- Number of neurons
- Activation functions
- Epochs
- Batch sizes

### 6. Final Reflection
The project demonstrates:
- Neural network learning process
- Forward propagation
- Loss calculation
- Backpropagation
- Weight and bias optimization

---

## Results
The neural network model achieved effective customer churn prediction performance with strong testing accuracy and balanced learning behavior.

---

## Repository Structure

part-1-neural-network-analysis/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── confusion_matrix.png
    ├── training_validation_graph.png
    └── model_comparison_table.csv

---

## Conclusion
A feed-forward neural network model was successfully built and evaluated for customer churn prediction. The project demonstrated preprocessing, neural network learning, model evaluation, and hyperparameter tuning techniques effectively.
