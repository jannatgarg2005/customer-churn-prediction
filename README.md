# 📊 Customer Churn Prediction

### End-to-End Machine Learning Pipeline | XGBoost · Scikit-learn · Streamlit

An end-to-end Machine Learning project that predicts customer churn in the telecommunications industry using **XGBoost, Scikit-learn, and Streamlit**. The application analyzes customer demographics, account information, subscription details, and service usage patterns to identify customers who are likely to discontinue their telecom services.

The project aims to help businesses understand customer behavior, identify potential churn risks, and make data-driven decisions to improve customer retention. By leveraging machine learning, the system provides churn predictions through an interactive web application, making the model accessible to users without requiring technical knowledge.

The model achieves an **F1-score of 84%**, demonstrating its ability to balance precision and recall when identifying customers who may leave the service.

## 🚀 Key Features

- **Customer Churn Prediction:** Predicts whether a customer is likely to leave a telecom service based on available customer information.
- **XGBoost Classifier:** Uses a gradient-boosting algorithm to learn patterns from historical customer data.
- **Data Preprocessing:** Handles data preparation, feature transformation, and encoding of categorical variables as required by the dataset.
- **Model Evaluation:** Evaluates model performance using classification metrics, including the F1-score.
- **Interactive Web Application:** Provides a user-friendly interface built with Streamlit for making predictions.
- **End-to-End ML Pipeline:** Integrates data preprocessing, model training, evaluation, and prediction into a complete workflow.
- **Data-Driven Retention Insights:** Helps businesses identify potentially at-risk customers and prioritize retention efforts.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Machine Learning:** XGBoost, Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn (if used)
- **Web Framework:** Streamlit
- **Model Evaluation:** F1-score, Precision, Recall, and Accuracy

## ⚙️ How It Works

1. **Data Collection:** Load the telecom customer dataset containing relevant customer and service information.
2. **Data Preprocessing:** Clean and prepare the data, handle missing values if present, and transform categorical features into a suitable format.
3. **Feature Engineering:** Select and prepare relevant features that may influence customer churn.
4. **Model Training:** Train an XGBoost classifier using the prepared dataset.
5. **Model Evaluation:** Evaluate the trained model using appropriate classification metrics and assess its ability to identify churn cases.
6. **Prediction:** Generate churn predictions for customer records using the trained model.
7. **Web Deployment:** Use Streamlit to provide an interactive interface for exploring customer information and obtaining predictions.

## 📈 Model Performance

| Metric | Result |
|---|---|
| F1-Score | 84% |
| Algorithm | XGBoost Classifier |

The F1-score combines precision and recall into a single metric, making it useful for evaluating classification models when correctly identifying potential churners is important.

*Note: The reported F1-score should be associated with the relevant evaluation dataset and class definition. Add accuracy, precision, and recall values only after verifying them from your actual model results.*

## 💡 Business Applications

- Identify customers who may discontinue their subscriptions.
- Support targeted customer retention campaigns.
- Help businesses prioritize customers who may require additional attention.
- Understand patterns associated with customer churn.
- Support data-driven customer relationship management strategies.

The model provides predictions rather than guaranteed outcomes. Businesses can use these predictions alongside customer feedback and other relevant information to make better retention decisions.

## 📂 Project Structure

```text
customer-churn-prediction/
│
├── app.py                 # Streamlit application
├── train.py               # Model training script (if applicable)
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
├── data/                  # Dataset files (if included)
└── models/                # Saved model files (if included)
```

*Update the filenames and folders above to match your actual repository structure.*

## 🔧 Installation and Setup

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd customer-churn-prediction
```

### 2. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal to access the application.

## 🔮 Future Improvements

- Perform hyperparameter tuning to improve model performance.
- Compare XGBoost with other classification algorithms.
- Apply explainable AI techniques such as SHAP to understand feature contributions.
- Add customer risk segmentation based on predicted churn probability.
- Incorporate additional evaluation metrics and visualizations.
- Deploy the application to a cloud hosting platform.
- Explore methods for handling class imbalance, if present in the dataset.

## 🎯 Learning Outcomes

Through this project, I explored the development of an end-to-end machine learning application, including data preprocessing, feature preparation, supervised model training, classification evaluation, and interactive deployment using Streamlit.

This project strengthened my understanding of how machine learning can be applied to real-world business problems and how predictive models can support data-driven decision-making.

## 👨‍💻 Author

**Jannat Garg**

Machine Learning | Artificial Intelligence | Python

---

⭐ If you find this project useful, consider giving the repository a star!
