# 🏠 London House Data Analysis Using Python & Pandas

## 📌 Project Overview

This project focuses on performing data analysis and data cleaning using Python libraries like Pandas, Seaborn, and Matplotlib in Jupyter Notebook. The dataset contains information related to areas, crime records, house prices, and dates. Various data preprocessing and analysis operations were performed to extract meaningful insights from the dataset.

---

# 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas  
- Seaborn  
- Matplotlib  

---

# 📚 Libraries & Commands Used

## 🔹 Pandas Library

```python id="zwdb4w"
import pandas as pd
```

Used to perform data manipulation and analysis.

---

## 🔹 Reading CSV File

```python id="wz0p6k"
pd.read_csv()
```

Used to import the CSV dataset into Jupyter Notebook.

---

## 🔹 Counting Non-Null Values

```python id="2pr1cl"
df.count()
```

Counts the number of non-null values in each column.

---

## 🔹 Checking Missing Values

```python id="90dyob"
df.isnull().sum()
```

Detects missing/null values from the dataframe.

---

## 🔹 Seaborn Library

```python id="3tpv3u"
import seaborn as sns
```

Used for data visualization.

---

## 🔹 Matplotlib Library

```python id="b5ghzd"
import matplotlib.pyplot as plt
```

Used for plotting graphs and charts.

---

## 🔹 Heatmap for Missing Values

```python id="ssr7mw"
sns.heatmap(df.isnull())
```

Displays missing values using a heatmap.

---

## 🔹 Display Plot

```python id="hq1i4u"
plt.show()
```

Used to display the graph.

---

## 🔹 Checking Data Types

```python id="z6d5v5"
df.dtypes
```

Shows datatype of each column.

---

## 🔹 Convert Date Column to Datetime

```python id="0k6ey4"
pd.to_datetime(df.Date)
```

Converts the Date column into datetime format.

---

## 🔹 Extracting Year

```python id="7y5mj6"
df.Date.dt.year
```

Creates a column containing only year values.

---

## 🔹 Extracting Month

```python id="av7jmi"
df.Date.dt.month
```

Creates a column containing only month values.

---

## 🔹 Insert New Column

```python id="4i4k8u"
df.insert()
```

Used to insert a new column at a specific position.

---

## 🔹 Drop Columns

```python id="c4d6ju"
df.drop()
```

Removes columns permanently from dataframe.

---

## 🔹 Grouping Data

```python id="1e9o89"
df.groupby()
```

Groups data based on unique column values.

---

## 🔹 Filtering Records

```python id="n5wzk6"
df[df.Column == 'Value']
```

Used to filter specific records.

---

## 🔹 Group By with Mean

```python id="f0q4gm"
df.groupby('Col_1')['Col_2'].mean()
```

Calculates mean values after grouping data.

---

# 📊 Tasks Performed

## ✅ Q1. Convert Datatype of 'Date' Column

- Converted the Date column into Date-Time format using `pd.to_datetime()`.

---

## ✅ Q2. Create 'Year' Column

- Added a new column named `year` containing only year values from the Date column.

---

## ✅ Q2(B). Create 'Month' Column

- Added a new column named `month` as the second column containing month values.

---

## ✅ Q3. Remove 'Year' and 'Month' Columns

- Deleted the columns `year` and `month` from the dataframe.

---

## ✅ Q4. Records Where No. of Crimes is 0

- Filtered all records where the number of crimes is zero and counted those records.

---

## ✅ Q5. Maximum & Minimum Average Price Per Year in England

- Used grouping functions to find maximum and minimum house prices per year in England.

---

## ✅ Q6. Maximum & Minimum Number of Crimes Per Area

- Calculated highest and lowest crime records for each area.

---

## ✅ Q7. Count of Records Where Average Price < 100000

- Displayed total count of records area-wise where average house price is less than 100000.

---

# 📈 Key Learnings

- Data Cleaning  
- Handling Missing Values  
- Data Transformation  
- Grouping & Filtering Data  
- Data Visualization  
- Extracting Insights from Dataset  
- Working with Real-World Datasets  
- Exploratory Data Analysis using Pandas  

---

# 📁 Project Structure

```bash id="mwlztj"
London-House-Data-Analysis/
│
├── London_House_Data_Analysis.ipynb
├── london_house_prices.csv
├── README.md
```

---

# ▶️ How to Run the Project

1. Clone the repository  

```bash id="2rjhmn"
git clone <your-repository-link>
```

2. Open the project folder  

3. Launch Jupyter Notebook  

```bash id="o2rm4h"
jupyter notebook
```

4. Open the notebook file and run all cells  

---

# 📚 Conclusion

This project helped in understanding data cleaning, handling missing values, data transformation, grouping, filtering, and visualization techniques using Python. The project improved practical knowledge of Pandas operations and data analysis techniques commonly used in real-world datasets.

It also provided hands-on experience in extracting meaningful insights from housing and crime datasets using Exploratory Data Analysis (EDA).

---

# ⭐ Author

**Tadi Rishitha**  
Aspiring Data Analyst | Python | Pandas | SQL | Power BI | Excel



