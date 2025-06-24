## 🌤️ Weather Analysis

A Python-based data analysis project to explore and visualize weather data using `pandas`.

---

### 🔍 Features

- ✅ Filter weather data by conditions like visibility, humidity, wind speed
- 📊 Compute summary statistics (mean, min, max) per weather condition
- 🔎 Query data with custom filters
- 💾 Read data from `.csv` or Excel format

---

### 🛠️ Technologies Used

- Python
- pandas
- Jupyter Notebook

---

### ⚙️ Function

It is a project of Data Analysis with Python or you can say, Data Science with Python.
The function that I used in this project :

* head() 
* shape 
* index 
* columns 
* dtypes 
* unique() 
* nunique() 
* count 
* value_counts 
* info() 
* groupby()
* mean()
* median()
* std()
* var()

---

### ❓ Question & Analysis

Below are the key analytical questions solved during this Weather Data Analysis project:

1. **Find all the unique 'Wind Speed' values in the data.**  
   → Retrieved all unique wind speed values using pandas `.unique()` function.

2. **Find the number of times when the 'Weather is exactly Clear'.**  
   → Filtered the DataFrame where `Weather == "Clear"` and counted occurrences.

3. **Find the number of times when the 'Wind Speed was exactly 4 km/h'.**  
   → Queried rows where wind speed is 4 and counted them.

4. **Find out all the Null Values in the data.**  
   → Used `.isnull().sum()` to check for missing data in each column.

5. **Rename the column name 'Weather' to 'Weather Condition'.**  
   → Applied `.rename()` function to update the column name.

6. **What is the mean 'Visibility'?**  
   → Calculated using the `.mean()` method on the `Visibility_km` column.

7. **What is the Standard Deviation of 'Pressure' in this data?**  
   → Used `.std()` to compute standard deviation of the `Pressure_kPa` column.

8. **What is the Variance of 'Relative Humidity' in this data?**  
   → Applied `.var()` to find variance in `Rel Hum_%`.

9. **Find all instances when 'Snow' was recorded.**  
   → Filtered rows where 'Weather Condition' contains the word "Snow".

10. **Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.**  
    → Applied logical condition to filter using both criteria.

11. **Find all instances when:**  
    a) *Weather is Clear and Relative Humidity is greater than 50*,  
    **OR**  
    b) *Visibility is above 40*  
    → Used combined logical conditions to filter the data.


