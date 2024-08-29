
## Algerian Forest Fires Dataset - Data Cleaning, EDA & Feature Engineering

### About the Dataset
The Algerian Forest Fires dataset includes data from two regions in Algeria: Bejaia (northeast) and Sidi Bel-abbes (northwest), collected between June and September 2012. The dataset consists of 244 instances, with 122 from each region, containing weather observations and fire-related indices. The data has been classified into two categories: **Fire** (138 instances) and **Not Fire** (106 instances).

### Attribute Information:
1. **Date**: Day, month, year (2012)
2. **Temperature**: Max temperature in °C
3. **RH**: Relative Humidity (%)
4. **Ws**: Wind speed (km/h)
5. **Rain**: Total precipitation (mm)
6. **FWI Components**: Fine Fuel Moisture Code (FFMC), Duff Moisture Code (DMC), Drought Code (DC), Initial Spread Index (ISI), Buildup Index (BUI), Fire Weather Index (FWI)
7. **Class**: Fire or Not Fire

---

## Data Cleaning
The dataset contained missing values, which were handled by:
- Splitting the dataset based on region.
- Adding a new column, "Region," to identify data from each region:
  - `0` for Bejaia Region Dataset.
  - `1` for Sidi-Bel Abbes Region Dataset.

---

## Feature Engineering
A new feature was introduced based on the regions, and irrelevant columns were removed or adjusted where necessary. This step helped improve model performance during future modeling phases by distinguishing regional characteristics.

---

## Exploratory Data Analysis (EDA)
The EDA process included:
- Visualizing the relationship between features like temperature, relative humidity, wind speed, and fire incidents.
- Investigating the distribution of fire and non-fire incidents across regions and time.
- Analyzing the correlation between weather attributes and fire occurrences.

---

## Insights
- **Most Fire accidents Months**:Most of the fires happened in August and very high Fires happened in only 3 months - June, July and August.
- **Wind Speed**: Increased wind speeds contributed to the spread of fires.
- **Fire accidents frequency**: Fire accidents occurred 56.5% of the time in the given dataset..

Check file for detailed visualizations and commentary on these insights.

---

## Conclusion
This project involved thorough data cleaning, feature engineering, and EDA, revealing crucial factors influencing forest fires in Algeria. These insights are valuable for predicting and preventing fire incidents based on weather conditions.
