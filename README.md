
# Building a dashboard to Identify Health Care Discrimination

## Project Overview
This project focuses on analyzing patient survey data to identify potential healthcare discrimination across different hospitals and states. Using the HCAHPS Hospital Ratings Survey dataset, we aim to uncover patterns and insights that could indicate systemic issues in patient care quality. The analysis was conducted using Google Colab, leveraging Python libraries for data processing and visualization.

**Note:** There is no interactive dashboard included in this project. The analysis and visualizations are presented through static visualizations created in Google Colab.

### Links:
- **Code Notebook**: [HCAHPS_analysis.ipynb](https://colab.research.google.com/drive/1PJ5Pr6ejJJTX32OqzZN-MUPwxHzeJMf3#scrollTo=7ZIONUNpeZIF)

## Objectives
- **Trend Analysis**: Visualize the distribution of survey response rates and patient survey star ratings.
- **Geographic Analysis**: Examine average patient survey star ratings across different states.
- **State-Specific Analysis**: Focus on Minnesota to uncover insights relevant to the University of Minnesota.
- **Correlation Analysis**: Explore the relationship between survey response rates and patient survey star ratings.

## Data Sources
- **HCAHPS Hospital Ratings Survey**: Patient experience ratings from 2018-2020, sourced from Medicare.gov.

## Tools and Technologies
- **Python**: The primary programming language used for data processing and analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib and Seaborn**: Used for creating visualizations.
- **Google Colab**: Environment for developing and testing the code.

## Key Steps and Methodologies
1. **Data Acquisition**: Loading and inspecting the HCAHPS dataset.
2. **Data Cleaning and Preprocessing**: Handling missing values, converting data types, and preparing the data for analysis.
3. **Exploratory Data Analysis (EDA)**: Initial exploration to understand the dataset structure and key statistics.
4. **Visualizations**:
   - **Distribution of Survey Response Rates**: Histogram to visualize the overall distribution.
   - **Distribution of Patient Survey Star Ratings**: Bar chart to show the frequency of each star rating.
   - **Average Patient Survey Star Rating by State**: Bar chart and heatmap to compare ratings across states.
   - **Boxplot of Survey Response Rates by State**: To identify variations and outliers in survey response rates.
   - **Minnesota-Specific Analysis**: Focused visualizations for hospitals in Minnesota.

## Data Visualization and Insights

### Distribution of Survey Response Rates
![Distribution of Survey Response Rates](file-acOmYa3zpHlwao4PBF5R9ExD)

- **Insight**: Most hospitals have a survey response rate around 30%, with some outliers indicating higher engagement. This clustering around 30% suggests that many hospitals are able to achieve a moderate level of patient engagement, but there are opportunities to increase this rate. High response rates might be linked to better patient engagement practices or more accessible survey methods.

### Distribution of Patient Survey Star Ratings
![Distribution of Patient Survey Star Ratings](file-k5kEg0I3w335htvQfFttW33p)

- **Insight**: The majority of hospitals are rated 3 or 4 stars, indicating that patient experiences are generally average to above average. However, there are fewer hospitals with extreme ratings (1-star or 5-star), suggesting that while most hospitals provide satisfactory care, exceptional or particularly poor patient experiences are less common.

### Average Patient Survey Star Rating by State
![Average Patient Survey Star Rating by State](file-yWvAJtvYNE7Fy1YMECZaILzK)

- **Insight**: States like South Dakota, Wisconsin, and Nebraska have the highest average star ratings, suggesting better overall patient experiences in these areas. On the other hand, states like Puerto Rico and Washington D.C. have lower average ratings, highlighting potential issues in healthcare quality that might need addressing. This geographic disparity might be due to various factors, including differences in healthcare infrastructure, state policies, and socioeconomic conditions.

### Heatmap of Average Hospital Ratings by State
![Heatmap of Average Hospital Ratings by State](file-MIRuYBfXDh4PjJZqM1BSdCY4)

- **Insight**: The heatmap visually highlights average ratings across states, showing regions with consistently high or low ratings. States in the Midwest and Northeast generally have higher ratings, while some Southern and Western states have lower ratings. This geographic pattern suggests that certain regions might have systemic healthcare issues needing targeted interventions.

### Boxplot of Survey Response Rates by State
![Boxplot of Survey Response Rates by State](file-k1tdbLOgM2YJzMtTeaWe8WiS)

- **Insight**: There is significant variation in survey response rates across states, with some states showing much higher median response rates. Outliers in some states indicate certain hospitals have exceptionally high or low response rates, which could skew overall state averages. Learning from states with higher response rates could provide strategies to improve engagement in other regions.

### Insights for Minnesota

**Average Patient Survey Star Rating by Hospital in Minnesota**
![Average Patient Survey Star Rating by Hospital in Minnesota](file-zi4wLKod53DkFg339mezAI1q)

- **Insight**: In Minnesota, there's a wide range of hospital ratings, with several hospitals achieving high ratings (4-5 stars). However, some hospitals have much lower ratings, indicating variability in patient experience within the state. Focusing on improving lower-rated hospitals could help elevate the overall standard of care.

**Distribution of Patient Survey Star Ratings in Minnesota**
![Distribution of Patient Survey Star Ratings in Minnesota](file-kXGFtzaUoJT4AbxJoEWSbkEm)

- **Insight**: Similar to the national trend, most hospitals in Minnesota have 3 or 4-star ratings. This consistency suggests that patient experiences in Minnesota are generally in line with national averages.

**Distribution of Survey Response Rates in Minnesota**
![Distribution of Survey Response Rates in Minnesota](file-YxQUR7k8ZrCDNIYTSzIqclOM)

- **Insight**: The response rate distribution in Minnesota peaks around 30%, consistent with the national average. This indicates that patient engagement in survey responses is comparable to the rest of the country, though there is always room for improvement.

### Conclusion and Next Steps:
- **Geographic Disparities**: Address disparities in patient ratings across different states by analyzing state-specific factors.
- **Targeted Improvements**: Focus on lower-rated hospitals in high-performing states to identify and replicate best practices.
- **Response Rates**: Investigate methods to improve survey response rates, particularly in states and hospitals with low engagement.
- **Systemic Issues**: Further analyze socio-economic and policy-related factors contributing to lower ratings in certain states.

These insights provide a comprehensive understanding of the current state of patient experiences across the country, highlighting areas that need attention and potential strategies for improvement.

## How to Use
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: pandas, matplotlib, seaborn.
3. **Run the Notebook**: Execute the Jupyter notebook in Google Colab or any local Jupyter environment to generate the visualizations.

## Acknowledgements
- **Medicare.gov**: For providing access to comprehensive HCAHPS survey data.
- **Google Colab**
- **Pandas, Matplotlib, Seaborn**: For data manipulation and visualization 

## Citation
- Centers for Medicare & Medicaid Services. HCAHPS Hospital Ratings Survey.
