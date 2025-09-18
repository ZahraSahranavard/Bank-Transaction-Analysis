# 🪙 Bank Transaction Analysis

![Bank Transaction Analysis](https://github.com/ZahraSahranavard/Bank-Transaction-Analysis/blob/main/Image/Banking_transaction_data_analysis.png)


## 📌 Project Overview

This project provides an in-depth analysis of a real banking transaction dataset to uncover valuable insights into customer behavior, peak transaction times, and product sales performance. The analysis leverages Python’s data science ecosystem to transform raw data into actionable insights.

The primary goals of this analysis are to answer the following questions:

*   **Q1:** Is there a specific pattern in customer purchase timing (day of the week, time of day)?
*   **Q2:** Which stores have the most sales?
*   **Q3:** What are the best-selling products?
  
## ⚙️ Methodology

### 🔹 Data Preprocessing
- Checking for missing values (`NaN`)  
- Convert Jalali dates to Gregorian using `jdatetime`  
- Create new time-based features (day_of_week, hour)  

### 🔹 Exploratory Data Analysis (EDA)
- Identify peak hours and days for transactions  
- Analyze total sales by store and product  
- Generate visualizations for better interpretation  

### 🔹 Insights Generation
- Detect seasonal or weekly patterns  
- Rank stores/products by performance
  
## 🛠️ Dependencies

The following Python libraries are required to run the analysis:

*   `pandas`: For data manipulation and analysis.
*   `matplotlib`: For data visualization.
*   `jdatetime`: For converting Shamsi (Jalali) dates to Gregorian dates.

You can install these dependencies using pip:

```bash
pip install pandas matplotlib jdatetime 
```

## 🚀 Usage

#### 1. Clone the repository:
```bash
git clone https://github.com/ZahraSahranavard/Bank-Transaction-Analysis
```
```bash
cd Bank-Transaction-Analysis
```
#### 2. Open the Jupyter Notebook:
```bash
Banking_transaction_data_analysis.ipynb
```
#### 3. Run the notebook cells to reproduce the analysis and visualizations
<br>

## 🔮 Future Enhancements

- Integration with machine learning models for sales forecasting
- Development of an interactive dashboard (using Plotly/Dash or Streamlit)
- Additional insights such as customer segmentation and basket analysis

For further improvements to this project, I have planned some advancements. Follow this repository to stay updated on them.😃

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📬 Contact
Developed by [Zahra Sahranavard](https://www.linkedin.com/in/zahra-sahranavard)  
For inquiries: zahra.sahranavard7622@iau.ir




