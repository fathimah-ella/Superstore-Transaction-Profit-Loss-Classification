# Superstore Transaction Profit/Loss Classification

## Project Overview
This analytical project focuses on **classifying Superstore transactions** into profit or loss categories. Utilizing the **Random Forest Classification** method, a supervised learning approach, this project analyzes transaction data to identify patterns, predict profitability, and present the results interactively via Streamlit.

## Dataset
The dataset used is **SuperStoreOrders** (in .csv format). This dataset contains detailed sales transaction information, including profit/loss figures and various attributes from a simulated superstore environment, commonly used for educational and analytical purposes.

**Source:** [www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset?resource=download)

## Methodology
This project follows a comprehensive data analysis workflow:
1.  **Data Exploration:** Displaying general information about the dataset, checking for missing values and outliers, performing descriptive statistical analysis, and creating initial visualizations to understand data patterns.
2.  **Data Preparation:** Handling missing values, adding new features, performing One-Hot Encoding on categorical variables, normalizing or standardizing numerical features (if necessary), and removing duplicate data to ensure a clean and ready-to-process dataset.
3.  **Modeling:** Creating a target column (`profit_class`), separating features and target, splitting data into training and testing sets, then training a **Random Forest Classification** model using the training data.
4.  **Prediction and Model Evaluation:** Evaluating the model's accuracy, and analyzing the importance level of each feature (*feature importance*) in the prediction.
5.  **Results Reporting:** Loading the built model and presenting its results interactively using Streamlit for easy-to-understand visualizations.

## Technologies and Tools
* **Programming Language:** Python
* **Python Libraries:**
    * `pandas` and `numpy` for data manipulation and analysis.
    * `scikit-learn` for building classification models and evaluation.
    * `matplotlib` and `seaborn` for static data visualization.
    * `streamlit` for building interactive dashboards and reporting.
    * `joblib` for saving and loading models.
* **Environment:** Google Colab (Jupyter Notebook)

## Key Results & Insights
* The Random Forest Classification model successfully predicted transaction profit/loss status with an **accuracy of 91.6%**.
* Feature importance analysis identified key factors influencing transaction profitability.
* An interactive Streamlit dashboard facilitates dynamic exploration of model results and data insights.

## How to Run the Notebook
1.  Ensure you have Python and the aforementioned libraries installed in your environment (you can use a `requirements.txt` file if available).
2.  Download the `Superstore_Profit_Loss_Analysis.ipynb` (or your chosen `.ipynb` file name) and `superstore_transactions.csv` files to your local directory.
3.  Open the notebook using Jupyter Notebook or upload it to Google Colab.
4.  Run each cell sequentially to reproduce the analysis and visualizations.
5.  **To run the Streamlit dashboard (if implemented in a separate `app.py` file):**
    * Save your Streamlit code (if exported from the notebook) to a file named `app.py`.
    * Open your terminal or command prompt, navigate to the directory where `app.py` is saved.
    * Run the command: `streamlit run app.py`

## Contact
[[Fathimah Ella Syarif](https://www.linkedin.com/in/fathimahellasyarif/)]
