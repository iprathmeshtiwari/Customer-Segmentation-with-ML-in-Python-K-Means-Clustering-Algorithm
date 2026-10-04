# Customer Segmentation using K-Means

## 📌 Project Overview

This project is a **Customer Segmentation System** built using **Python, Machine Learning, and Streamlit**.

The project uses the **K-Means Clustering** algorithm to group customers based on:

- Annual Income
- Spending Score

The goal is to identify different types of customers and help businesses understand their customer behavior and create better marketing strategies.

The project also includes a **Streamlit web application** where users can enter customer details and predict their customer segment.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit
- Plotly
- Jupyter Notebook

---

## 📂 Project Structure

```text
Customer Segmentation/
│
├── venv/
├── customer-segmentation.ipynb
├── customer_app.py
├── Mall_Customers.csv
├── customer_segmentation_model.pkl
├── Mall_Customers_Segmented.csv
├── requirements.txt
└── README.md
````

> `venv` is used only for the Python environment. Project files should remain outside the `venv` folder.

---

## 🚀 How to Run

### 1. Create and activate virtual environment

```powershell
python -m venv venv
.\venv\Scripts\activate
```

### 2. Install required libraries

```powershell
pip install pandas numpy matplotlib seaborn scikit-learn streamlit plotly joblib
```

### 3. Run the Streamlit application

```powershell
streamlit run customer_app.py
```

The application will open at:

```text
http://localhost:8501
```

---

## 📊 Machine Learning Workflow

```text
Load Dataset
     ↓
Data Analysis
     ↓
Feature Selection
     ↓
Elbow Method
     ↓
K-Means Clustering
     ↓
Customer Segmentation
     ↓
Save Model
     ↓
Streamlit Application
```

---

## 👥 Customer Segments

The project identifies five customer groups:

* **Careful Customers** – Low Income, Low Spending
* **Standard Customers** – Moderate Income, Moderate Spending
* **Target Customers** – High Income, High Spending
* **Careless Customers** – Low Income, High Spending
* **Sensible Customers** – High Income, Low Spending

---

## 💡 Key Learning

This project demonstrates an end-to-end machine learning workflow, including:

* Data analysis
* K-Means clustering
* Data visualization
* Model saving with Joblib
* Customer prediction
* Streamlit deployment
* Python virtual environment management

---

## 🔮 Future Improvements

* Add more customer features
* Improve the Streamlit UI
* Add more interactive visualizations
* Try other clustering algorithms
* Deploy the application online

```
```
👨‍💻 Conclusion

This project provides an end-to-end implementation of Customer Segmentation using K-Means Clustering, starting from dataset analysis and model training to model deployment through Streamlit.

The project also documents the setup, configuration, errors, troubleshooting, and solutions encountered during development, making it easier to reproduce and run the project in the future.
