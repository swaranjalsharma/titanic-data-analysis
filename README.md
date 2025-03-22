🛳️ Titanic Data Analysis and Visualization
This project dives deep into the legendary Titanic dataset, unraveling survival patterns and passenger demographics through data cleaning, exploratory data analysis (EDA), and visual storytelling.

📦 Dataset Used
Source: Titanic Dataset (titanic_cleaned.csv)

Columns: Passenger information including age, gender, ticket fare, class, port of embarkation, etc.

🧹 Data Cleaning Highlights
Converted all column names to lowercase

Set passengerid as the index

Extracted and normalized titles (e.g., Mr., Miss, Mrs., etc.)

Imputed missing values:

Age based on passenger title

Embarked based on external research

Cabin deck derived from cabin prefix

Created new columns:

family_size = sibsp + parch

fare_bin and age_group for better visualization

📊 Exploratory Data Analysis (EDA)
🔹 Univariate Analysis
Numerical columns: Histograms, boxplots, violin plots (e.g., fare, sibsp, family_size)

Categorical columns: Countplots, pie charts, bar charts (e.g., sex, pclass, embarked, title)

🔹 Bivariate Analysis
Survival rates analyzed against:

age and pclass

embarked

title

family_size

fare and solo travel by gender

Explored the impact of age group and ticket class on survival

🎯 Key Insights
1st class passengers and females had the highest survival rates

Solo male travelers had significantly lower chances of survival

Young children (especially in 1st class) had priority in rescue

Fare was a strong indicator of class and indirectly survival

Some unique titles (e.g., Sir, Lady, Capt.) reflected social status but didn’t guarantee survival

🛠️ Future Work
Build machine learning models to predict survival

Create an interactive dashboard (e.g., using Streamlit or Tableau)

Use advanced feature engineering for improved model performance

💡 Conclusion
This Titanic analysis project showcases how powerful insights can emerge from structured cleaning, thoughtful visualizations, and a curious mind. The iceberg may have taken the ship, but not our data clarity! 🚢📈
