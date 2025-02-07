# Medical Insurance Expense Prediction Dashboard

## Overview
The **Medical Insurance Expense Prediction Dashboard** is an interactive web application that predicts medical insurance expenses based on user-provided information. The application also provides insights into a dataset of historical medical insurance records, enabling users to explore trends and correlations between various factors and insurance costs.


## Features
1. **Medical Insurance Expense Prediction**:
   - Users can input their age, BMI, number of children, smoking habits, and region of residence to estimate their expected insurance expenses.
   - The prediction is based on a trained **Linear Regression Model**, ensuring accuracy and reliability.

2. **Data Insights**:
   - Explore the distribution of medical insurance expenses.
   - Visualize correlations between factors such as age, BMI, smoking habits, and insurance costs using heatmaps and histograms.

3. **Interactive User Experience**:
   - Intuitive and user-friendly interface built using **Streamlit**.
   - Clear navigation between sections, including Home, Data Insights, and Prediction.

4. **Enhanced Financial Planning**:
   - Helps users make informed decisions by understanding how different factors impact insurance expenses.
   - Enables better financial planning and transparency in insurance cost estimation.


## How It Works
- The dashboard uses a **Linear Regression Model** trained on a dataset of medical insurance records.
- The dataset includes factors such as age, BMI, number of children, smoking habits, and region.
- Upon receiving user inputs, the model processes the data and predicts the estimated medical insurance expenses dynamically.


## How to Use
1. **Home**:
   - Overview of the application and its purpose.
2. **Data Insights**:
   - Explore trends and patterns in the medical insurance dataset through interactive visualizations.
3. **Prediction**:
   - Enter details such as age, BMI, number of children, smoking status, and region.
   - Click the "Predict" button to receive an estimate of your medical insurance expenses.


## Requirements
- **Python 3.9+**
- Libraries:
  - `streamlit`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `joblib`


## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/medical-insurance-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd medical-insurance-dashboard
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Dataset
The application uses a dataset containing medical insurance records with the following columns:
- **Age**: Age of the individual.
- **BMI**: Body Mass Index, a measure of body fat.
- **Children**: Number of children covered by the insurance.
- **Smoker**: Smoking status of the individual.
- **Region**: Region of residence (northeast, northwest, southeast, southwest).
- **Expenses**: Medical insurance expenses incurred by the individual.


## Ownership
**Developed and Maintained by Saaimah Siraj**


