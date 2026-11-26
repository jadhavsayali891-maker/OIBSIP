## Task 2: Unemployment Analysis with Python

### 1. Project Overview
This project focuses on analysing unemployment data in India using Python. Exploratory Data Analysis (EDA) is performed to understand unemployment trends across different states and months, with special attention to the COVID-19 period.

### 2. Objective
The main objectives of this project are:
- Analyse unemployment rates across different regions of India.
- Identify monthly unemployment trends.
- Compare unemployment rates before and during the COVID-19 period.
- Visualise the data using different charts.
- Understand how unemployment changed during the COVID-19 period.

### 3. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### 4. Dataset
**Dataset Name:** Unemployment in India.csv

The dataset contains information about:
- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Rural/Urban)

After removing completely empty rows, the dataset contains **740 records and 7 columns** with no missing values.

### 5. Project Workflow

**Step 1: Data Loading**
- Imported the required Python libraries.
- Loaded the CSV dataset using Pandas.
- Displayed the first five rows.

**Step 2: Data Cleaning and EDA**
- Checked dataset shape and column names.
- Converted the Date column into datetime format.
- Converted numerical columns into numeric data types.
- Removed completely empty rows.
- Checked missing values and descriptive statistics.

**Step 3: Region-wise Analysis**
- Calculated the average unemployment rate for each region.
- Sorted regions from highest to lowest unemployment rate.

**Step 4: Monthly Analysis**
- Extracted month and year from the Date column.
- Calculated the monthly average unemployment rate.
- Identified changes in unemployment over time.

**Step 5: Data Visualisation**
The project includes visualisations such as:
- Monthly unemployment trend line chart.
- State-wise unemployment trend line chart for Maharashtra, Uttar Pradesh and West Bengal.
- Bar chart showing the top 10 regions with the highest average unemployment rate.
- Correlation heatmap of employment indicators.
- Pre-COVID and COVID-period comparison chart.

**Step 6: COVID-19 Impact Analysis**
- Divided the dataset into pre-COVID and COVID periods.
- Calculated the average unemployment rate for both periods.
- Compared the results to understand the change.

### 6. Key Findings

- Tripura recorded the highest average unemployment rate of approximately **28.35%**.
- Haryana recorded the second-highest average unemployment rate of approximately **26.28%**.
- Meghalaya recorded the lowest average unemployment rate of approximately **4.80%**.
- The monthly average unemployment rate reached approximately **24.88% in May 2020**.
- The average unemployment rate before COVID-19 was **9.51%**.
- The average unemployment rate during the COVID period was **17.77%**.
- The analysis shows a significant increase in unemployment during the COVID period.

### 7. Conclusion
This project helped analyse unemployment trends across different regions of India using Python. Data cleaning, exploratory data analysis and visualisation were used to understand regional differences and monthly changes.

The comparison between pre-COVID and COVID-period unemployment rates showed an increase from 9.51% to 17.77%. The findings highlight the major changes in unemployment during the COVID-19 period.

Overall, this project demonstrates the use of Python libraries for analysing real-world datasets and presenting meaningful insights through visualisations.

### 8. How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Keep the dataset and notebook in the same project folder.
4. Open Jupyter Notebook.
5. Open `Unemployment_Analysis.ipynb`.
6. Run the notebook cells from top to bottom.

### 9. Project Files

```text
DataScience-Task2-UnemploymentAnalysis/
│
├── Unemployment_Analysis.ipynb
├── Unemployment in India.csv
└── README.md
```

### 10. Internship Details

**Internship:** Oasis Infobyte (OIBSIP)  
**Domain:** Data Science  
**Task:** Task 2 – Unemployment Analysis with Python

