# ANN Classification - Customer Churn Prediction

This repository contains an Artificial Neural Network (ANN) model designed to predict customer churn based on various customer attributes. The model is implemented using Python, with Jupyter Notebooks for experimentation and Streamlit for deployment.

## 📁 Repository Structure

```
Ann-Classification/
├── models/                 # Directory for saving trained models
├── Churn_Modelling.csv     # Dataset used for training and evaluation
├── app.py                  # Streamlit app for model deployment
├── experiments.ipynb       # Notebook for model development and training
├── prediction.ipynb        # Notebook for making predictions
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## 📊 Dataset

The dataset used is `Churn_Modelling.csv`, which includes information about customers such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DV821/Ann-Classification.git
cd Ann-Classification
```

### 2. Install Dependencies

Ensure you have Python 3.x installed. Then, install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

To launch the deployed model interface:

```bash
streamlit run app.py
```

[Deployment Link](https://ann-classification-gdvn5ahmkevu7hmzmnebst.streamlit.app)

## 🧠 Model Architecture

The ANN model is structured as follows:

- **Input Layer**: Accepts preprocessed customer features.
- **Hidden Layers**: Two fully connected layers with ReLU activation functions.
- **Output Layer**: Single neuron with Sigmoid activation for binary classification.

## 📈 Model Training & Evaluation

The `experiments.ipynb` notebook covers:

- Data preprocessing (handling missing values, encoding categorical variables, feature scaling).
- Splitting the dataset into training and testing sets.
- Building and training the ANN model.
- Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.

## 🔮 Making Predictions

Use the `prediction.ipynb` notebook to:

- Load the trained model.
- Input new customer data.
- Predict the likelihood of customer churn.

## 📦 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- tensorflow
- keras
- streamlit
- matplotlib
- seaborn

Refer to `requirements.txt` for the complete list.

## 📬 Contact

For any questions or feedback, feel free to open an issue or reach out via [GitHub](https://github.com/DV821).

---

*This project is developed as part of an academic exploration into machine learning applications for customer retention strategies.*
