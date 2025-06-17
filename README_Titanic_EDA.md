# 📊 Titanic Dataset Analysis – Prodigy Data Science Internship Project

## 🗂 Project Name:
**Titanic Survivors EDA and Visualization**

## 📁 File Name:
`Prodigy_DS_02.ipynb`

## 👨‍💻 Description
This project explores and visualizes the Titanic dataset to uncover patterns and insights related to passengers' age, gender, fare, and embarkation. The goal is to understand the data structure and perform necessary preprocessing steps, followed by basic visual analysis.

## ⚙️ How It Works
1. **Data Loading**: Reads `test.csv` using `pandas`.
2. **Data Cleaning**:
   - Removes missing values from `Embarked`.
   - Fills missing values in `Cabin` with `"Unknown"`.
   - Replaces missing `Age` values with the mean.
3. **Exploratory Analysis**:
   - Checks for duplicates and missing values.
   - Uses visualizations to analyze age distribution, gender distribution, and relationships between `Age`, `Fare`, and `Sex`.

## 📈 Key Features
- Histogram of Age Distribution.
- Gender distribution visualization using `seaborn`.
- Scatter plot of `Age` vs `Fare` colored by `Sex`.

## 🧰 Technologies Used
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## 🚀 How to Run
1. Clone the repository or download the `.ipynb` file.
2. Ensure `test.csv` is in the same directory.
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Open the notebook:
   ```bash
   jupyter notebook Prodigy_DS_02.ipynb
   ```
5. Run the cells sequentially.

## 📚 Skills Gained
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Handling missing and duplicate data
- Working with real-world datasets

## 🏁 Outcome
This project enhances the ability to derive insights from data through visual storytelling and lays the groundwork for more complex machine learning applications.
