# nvidia-stock-analysis

---

## 🗂️ Overview

This project analyzes **NVIDIA stock price data (July 2022 – July 2024)** using Python.  
The assignment explores **big-data processing**, **feature engineering**, **data visualization**, and **machine learning** techniques including **KMeans Clustering** and **LSTM regression**.

All code is written in a **Jupyter Notebook** and accompanied by a detailed report.

---

## 🎯 Objectives

- Load and clean real-world stock data  
- Engineer features (returns, moving average, normalized volume)  
- Create meaningful visualizations using matplotlib and seaborn  
- Apply unsupervised learning (KMeans)  
- Build LSTM-based time series forecasting model

---



## 📁 Project Structure

- `notebook/HW1_DIC.ipynb`: Main Jupyter Notebook containing all data processing and ML code  
- `report/Nvidia_Stock_Analysis_Report.pdf`: Final PDF report with explanations, visualizations, and insights  
- `data/NVDA.csv`: Historical stock price data for NVIDIA  
- `requirements.txt`: List of Python packages needed to run the notebook  
- `README.md`: This file

  ---

## 🧪 Key Tasks Performed

### 🔹 Part 1: Big Data Processing

- Cleaned missing values in stock data using forward fill and median techniques  
- Converted date formats for consistency  
- Calculated basic statistics (min, max, mean, median, std deviation)  
- Engineered features like daily returns and 7-day moving average  
- Normalized trading volume using Min-Max scaling  
- Visualized trends using histograms, boxplots, and heatmaps  

### 🔹 Part 2: Machine Learning

- Applied **KMeans Clustering** on normalized daily return, adjusted close, and volume  
- Identified and interpreted 3 clusters representing different market behaviors  
- Built an **LSTM model** using TensorFlow to predict closing prices  
- Evaluated model using Mean Squared Error and visual comparison  


---

## 📊 Libraries Used

- `pandas` – for data manipulation and analysis  
- `numpy` – for numerical computations  
- `matplotlib` & `seaborn` – for visualizations  
- `scikit-learn` – for clustering and preprocessing  
- `tensorflow` – for building and training the LSTM model  

To install all dependencies, run:

pip install -r requirements.txt



