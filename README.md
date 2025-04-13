# Trading with Neural Networks: A Long–Short Approach

This repository contains my individual project for the **Advanced Machine Learning** module, part of the **Computational Finance MSc** at University College London (UCL). The project investigates the use of machine learning models—including Logistic Regression, LSTM, CNN, and Wavelet-CNN—to forecast daily S&P 500 returns and construct profitable long–short trading strategies.

---

## Overview

- **Objective:**  
  Forecast next-day stock returns (relative to the cross-sectional median) and construct daily long–short portfolios based on predicted probabilities.

- **Methods:**  
  - **Data Preparation:** Rolling-window approach using 240-day return sequences for feature generation.  
  - **Modeling:** Comparison of logistic regression (baseline) with deep learning models: LSTM, CNN, and Wavelet-CNN.  
  - **Portfolio Construction:** Daily ranking of stocks by predicted probability to select the top 10 longs and bottom 10 shorts.  
  - **Evaluation:** Analysis of classification performance and key financial metrics (annualized returns, Sharpe ratio, drawdowns), with additional breakdowns by industry.

- **Extended Analysis:**  
  The final report is limited to 10–11 pages (excluding appendices), so additional analyses have been conducted in the accompanying notebook.

---

## Repository Structure

- **`final_report.pdf`**  
  The comprehensive report detailing the project's background, methodology, results, and discussion.

- **`notebook_final.ipynb`**  
  The Python notebook containing all code for data processing, model training, evaluation, and visualization.

- **Project Instructions Folder**  
  Contains the original project instructions and scope.

---

## Tools and Technologies

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Modeling:** Scikit-learn (for logistic regression), TensorFlow & Keras (for LSTM, CNN, and Wavelet-CNN)
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebooks

---

## Project Context

This project was completed as an individual assignment for the Advanced Machine Learning module within the Computational Finance MSc at UCL. The final report is limited to 10–11 pages (excluding appendices), which constrained the analysis scope; therefore, further exploration and model refinements are available in the accompanying notebook.

⸻

## Contact

For further discussion or inquiries, please contact me at tomas.romeiro@gmail.com

⸻
