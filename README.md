# Task5
# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights using data cleaning, visualization, and interpretation techniques.

---

## 📊 Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Plotly Express (for interactive visualizations)

---

## 🔍 Data Cleaning

- **Age**: Missing values filled using median grouped by Sex and Pclass.
- **Cabin**: Missing values replaced with 'Unknown'; first letter extracted to represent Deck.
- **Embarked**: Missing values filled with the most frequent category (mode).

---

## 📈 Observations (Based on Graphs)

1. **Survival by Gender**:
   - More males were on board than females.
   - Females had a significantly higher survival rate.

2. **Age Distribution**:
   - Right-skewed distribution.
   - Majority of passengers were between 20–30 years.
   - Some elderly outliers (Age > 70).

3. **Fare vs Age (Scatter Plot)**:
   - Survivors tended to have paid higher fares.
   - High-fare survivors mostly belonged to 1st class.

4. **Survival by Passenger Class**:
   - 1st class had the highest survival rate.
   - 3rd class had the lowest.

5. **Embarked vs Survival**:
   - Most passengers embarked from Southampton.
   - Survival was higher for those from Cherbourg.

6. **Deck Distribution**:
   - Passengers were mostly in Decks B–E.
   - Many entries were marked as Unknown (due to missing Cabin data).

---

## ✅ Summary of Insights

- Females and 1st class passengers had a higher chance of survival.
- Younger passengers (<30 years) had better survival rates.
- Higher fare amounts correlated with increased survival chances.
- Passengers who embarked from Cherbourg showed relatively better survival stats.
- Deck and Cabin data, though incomplete, still hinted at class and survival patterns.

---

## 📊 Plotly vs. Matplotlib: Comparison

- **Matplotlib** is a static plotting library that provides high control over visuals and is ideal for exporting plots in publication-quality formats like PNG or PDF.
- **Plotly**, on the other hand, offers interactive charts with hover effects, zoom, and tooltips, making it highly effective for presentations or dashboards.
- While **Matplotlib** is simple and flexible for basic data analysis, **Plotly** enhances storytelling with dynamic visual exploration.
- Both tools were used in this project to demonstrate how insights remain consistent across libraries, but user experience differs significantly.


