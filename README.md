**# Insurance Fraud Detection**

## Description
This Streamlit-based web application facilitates **insurance fraud detection** by utilizing machine learning models. Users can upload their dataset or use a provided sample dataset to analyze and classify fraudulent claims. The application performs **data preprocessing, exploratory data analysis (EDA), and model training** using Logistic Regression and Random Forest Classifiers.

## Features
- **Data Upload**: Users can upload CSV/XLSX files or use a sample dataset.
- **Exploratory Data Analysis (EDA)**: Generates a correlation heatmap for feature insights.
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.
- **Model Training**: Supports Logistic Regression and Random Forest Classifiers.
- **Model Evaluation**: Provides classification reports, confusion matrices, and fraud prediction visualizations.

## Tech Stack
- **Python**
- **Streamlit** (UI)
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (Machine Learning)
- **Seaborn, Matplotlib, Plotly** (Visualization)

## Installation
Clone the repository and install the required dependencies.

```bash
git clone https://github.com/your-username/insurance-fraud-detection.git
cd insurance-fraud-detection
pip install -r requirements.txt
```

## Usage
Run the Streamlit application:

```bash
streamlit run app.py
```

## Folder Structure
```
insurance-fraud-detection/
│-- app.py  # Main Streamlit application
│-- requirements.txt  # Dependencies
│-- README.md  # Documentation
│-- sample_data.xlsx  # Sample dataset
```

## Future Enhancements
- Implement more machine learning models (XGBoost, Neural Networks)
- Improve feature engineering for better fraud detection
- Deploy the application using cloud services

## License
This project is open-source under the MIT License.

---
### Contributors
- **Sisira S** (https://github.com/Sisira121)

