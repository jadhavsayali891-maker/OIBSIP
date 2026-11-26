# Car Price Prediction with Machine Learning

## About the Project
This is my third project for the Oasis Infobyte Data Science Internship.

In this project, I worked on predicting the selling price of used cars using machine learning. I used car details like present price, kilometres driven, fuel type, transmission and car age to build prediction models.

## Tools I Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset
I used the CarDekho car dataset. It contains information about used cars, including their year, selling price, present price, kilometres driven, fuel type, seller type, transmission and previous owners.

After removing duplicate records, the dataset contained 299 rows.

## What I Did
1. Loaded the car dataset and checked its details.
2. Checked missing values and duplicate records.
3. Removed duplicate rows and cleaned categorical values.
4. Created a new feature called `Car_Age`.
5. Extracted the car brand from the car name.
6. Created graphs to understand car prices and other features.
7. Used One-Hot Encoding for categorical data.
8. Created a correlation heatmap.
9. Divided the data into training and testing sets.
10. Trained Linear Regression and Random Forest models.
11. Compared the models using MAE, RMSE and R² score.
12. Compared feature contributions using a chart.

## Model Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.35 | 2.39 | 0.78 |
| Random Forest | 1.33 | 3.20 | 0.60 |

Linear Regression performed better overall based on its RMSE and R² score. Random Forest had a slightly lower MAE.

## What I Learned
Through this project, I learned how to prepare data for machine learning, create new features, encode categorical values and train regression models. I also learned how to compare models using different evaluation metrics.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn`

3. Keep `car data.csv` in the project folder.
4. Open `Car_Price_Prediction.ipynb`.
5. Run the notebook cells one by one.

**Internship:** Oasis Infobyte – Data Science Internship (OIBSIP)