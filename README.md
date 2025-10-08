# Lamboson_Manlolo_Philippines Monthly Typhoon Trend (2014-2024)

## 1. Group Information
- Group Name: Cloud Breakers
- Members:
  
   Lamboson, Jaycel L.
  
   Manlolo, Noel Alexis C.
  
- Assigned Theme: **Weather**
- Topic: **Phillippines Monthly Typhoon Trend (2014-2024)**

## 2. Project Overview
- Dataset Title: Philippines Monthly Typhoon Trend (2014–2024)
- Source (URL or reference): Source: https://www.kaggle.com/datasets/denvermagtibay/philippines-monthly-typhoon-trend-2014-2024
- License/Attribution: This dataset was created and shared by Denver Magtibay on Kaggle. It is intended for public and educational use, and proper credit should be given to the original author when used or cited.

- Objective:
  
<p align="justify">
To analyze the Philippines’ monthly typhoon data from 2014 to 2024 and reveal patterns in typhoon frequency across months and years. This dataset aims to show seasonal trends, peak typhoon months, and variations in annual typhoon activity.
</p>

## 3. Preprocessing Summary
The preprocessing techniques that was use are:
1. Data Cleaning
2. Data Transformation
3. Data Reduction

## 4. Visualizations

### Visualization 1: Histogram of Typhoon Counts per Year
This histogram shows how the total number of typhoons changed each year from 2014 to 2024. It helps us visualize overall trends and the frequency of typhoon occurrences annually.

<p align="center">
<img src="https://github.com/user-attachments/assets/17cea229-7a67-487c-9a02-cbc8973370be" width="800">

The distribution indicates that most years experience a moderate number of typhoons, with occasional peaks showing particularly active years.

---

### Visualization 2: KDE Plot of Monthly Typhoon Frequency
This Kernel Density Estimate (KDE) plot highlights the distribution of monthly typhoon occurrences. It helps identify months with the highest likelihood of typhoon activity.

<p align="center">
<img src="https://github.com/user-attachments/assets/49824b4d-b3fd-4852-89a2-7da8d610f412" width="800">
  
The density curve shows that typhoon frequency increases during mid to late months of the year, aligning with the wet season (around July to October).

---

### Visualization 3: Scatter Plot — Month vs. Typhoon Count
This scatter plot displays the relationship between months and the number of typhoons recorded. It allows us to visually identify seasonal patterns and variability across months.

<p align="center">
<img src="https://github.com/user-attachments/assets/3b125742-0b81-4174-b7e4-2efe929d819a" width="800">
  
The plot clearly shows clustering around the mid-year months, suggesting that most typhoons occur between June and November.

---

### Visualization 4: Pairplot — Number of Typhoons, Month, and Year
This pairplot explores the relationships among the year, month, and number of typhoons. It provides a multi-variable view that can reveal underlying trends or correlations.

<p align="center">
<img src="https://github.com/user-attachments/assets/a49933b9-6b1d-471a-9a8a-72b1bad2bf31" width="800">

The scatter relationships indicate that typhoon counts vary seasonally but remain relatively consistent across the decade.

---

### Visualization 5: Correlation Matrix of Numeric Variables
This heatmap displays correlations among numeric variables such as year, month, and number of typhoons. It helps determine which variables are most related to one another.

<p align="center">
<img src="https://github.com/user-attachments/assets/b83e5625-9eb3-4680-a886-e46678c4428d" width="800">

The correlation values show that month and typhoon count are somewhat related due to seasonality, while year has a weaker correlation, suggesting no clear long-term increase or decrease.

---

### Visualization 6: Missingness Plot
This plot helps us identify if there are missing or incomplete data points in the dataset. By visualizing the presence of null values, we can determine whether the dataset is complete or needs cleaning before analysis.

<p align="center">
<img src="https://github.com/user-attachments/assets/289f6fed-1471-4aab-bbd4-4ad32564c265" width="800">

Based on the plot, there appear to be no missing or incomplete values — indicating that the dataset is clean and ready for analysis.

---

### Visualization 7: Typhoon Counts per Season (Wet vs Dry)
This bar plot compares the total number of typhoons that occurred during the wet and dry seasons. It allows us to see which season experiences more typhoon activity in the Philippines.

<p align="center">
<img src="https://github.com/user-attachments/assets/4790561b-1a83-46da-b348-acc657caf829" width="800">

The wet season shows a significantly higher number of typhoons compared to the dry season, which aligns with the country’s typical climate pattern from June to November.

---

### Visualization 8: Distribution of Typhoons per Month Across Years
This boxplot shows how the number of typhoons varies for each month from 2014 to 2024. It helps identify months with high variability or outliers, such as unusually strong typhoon seasons.

<p align="center">
<img src="https://github.com/user-attachments/assets/d20e9202-f735-489b-916d-4b2d12463048" width="800">

Months like June to October tend to have higher median values and more outliers, suggesting these are peak typhoon months, while February to May have fewer events.

---

### Visualization 9: Monthly Typhoon Counts Across 2014–2024
This line plot displays how the number of typhoons has changed over time. It highlights upward or downward trends in typhoon frequency throughout the years.

<p align="center">
<img src="https://github.com/user-attachments/assets/a3720e7b-4621-4594-aa03-e5ab6cd50679" width="800">

The plot shows fluctuations in typhoon activity, with 2020 and 2024 experiencing the highest number of typhoons, while other years remain relatively stable.

---

### Visualization 10: Clustering of Years by Typhoon Trends
This clustering visualization groups years based on their total typhoon counts using K-Means. It helps us identify patterns, such as which years had similar levels of typhoon activity (low, moderate, or high).

<p align="center">
<img src="https://github.com/user-attachments/assets/a1c4d3b0-1fc3-436c-b973-2e813ebb8433" width="800">

The clusters show clear distinctions among years with low, moderate, and high typhoon activity — indicating that some periods were more active than others in terms of storm frequency.

---

## 5. Key Insights

### 1. Typhoon activity is highly seasonal.
Most typhoons occur between June and November, which aligns with the Philippines’ wet season, peaking around August to October.

### 2. Yearly typhoon counts remain relatively stable.
From 2014 to 2024, the total number of typhoons per year fluctuates slightly but shows no strong upward or downward trend overall.

### 3. The wet season experiences significantly more typhoons than the dry season.
Barplot analysis confirms that over two-thirds of all typhoons occur during the wet season, emphasizing its climatic impact.

### 4. Outliers and high variability are observed in mid-year months.
Boxplot results reveal that months like July to October occasionally experience unusually high typhoon counts compared to other months.

### 5. Clustering shows distinct groups of typhoon activity levels.
K-Means analysis groups the years into low, moderate, and high-activity clusters, indicating that some years experienced notably more storms.
