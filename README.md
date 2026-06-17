# 🚗 US Accidents Analysis - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of a data science internship task focused on analyzing traffic accident data from the **US Accidents dataset**.

The goal is to perform **Exploratory Data Analysis (EDA)** to uncover patterns related to accident severity, time of occurrence, weather conditions, and road infrastructure.

Due to computational limitations, a **sample of 100,000 records** was used instead of the full dataset.

---

## 📂 Dataset Description

The dataset contains information about traffic accidents in the United States, including:

- Accident severity
- Time and date of occurrence
- Geographic location
- Weather conditions
- Road infrastructure features


---

## 🧹 Data Preprocessing

The following preprocessing steps were applied:

- Removal of columns with 100% missing values
- Conversion of temperature from °F to °C
- Conversion of distance from miles to kilometers
- Conversion of visibility from miles to kilometers
- Conversion of wind speed from mph to km/h
- Conversion of datetime columns to proper datetime format

---

## 📊 Exploratory Data Analysis

### 1. Accident Severity Distribution

Most accidents belong to severity levels 2 and 3:

- Severity 2: ~55%
- Severity 3: ~45%
- Severity 1 & 4: very rare

---

### 2. Accidents by Time of Day

- Average accident time: ~1:30 PM  
- Median accident time: ~2:00 PM  

Accidents are more frequent during daytime hours when traffic activity is higher.

---

### 3. Day vs Night Analysis

- Day accidents: ~62.5%
- Night accidents: ~37.5%

Daytime traffic volume contributes significantly to accident frequency.

---

### 4. Weather Conditions

Most accidents occur under:

- Clear weather
- Overcast
- Mostly cloudy conditions

Rain-related conditions are less frequent but may increase risk due to reduced visibility and road friction.

---

### 5. Temperature Analysis

Temperature values were converted to Celsius to improve interpretability.  
Accidents occur across a wide range of temperature conditions.

---

### 6. Visibility Analysis

Lower visibility conditions can negatively impact driver reaction time and road awareness, potentially increasing accident risk.

---

### 7. Junction Analysis

- 10.4% of accidents occur at junctions
- 89.6% occur outside junctions

Most accidents are not concentrated at intersections.

---

### 8. Traffic Signal Analysis

- 10.7% near traffic signals
- 89.3% elsewhere

Traffic signals remain important but are not the primary location of accidents.

---

### 9. Geographical Distribution

- Majority of records come from **California**
- Limited data from Ohio and West Virginia

Geographical conclusions should be interpreted with caution.

---

## 📈 Key Insights

- Moderate severity accidents are the most common
- Accidents peak during daytime hours
- Weather and visibility play an important role
- Most accidents occur outside junctions and traffic signals
- Dataset is geographically imbalanced

---

## 🛠️ Technologies Used

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Conclusion

This EDA provides a clear understanding of traffic accident patterns and highlights key factors such as time, weather, and infrastructure.

It serves as a foundation for future **predictive modeling and machine learning applications**.

---

##  Author

Student project - Data Science Internship Task (Prodigy InfoTech)