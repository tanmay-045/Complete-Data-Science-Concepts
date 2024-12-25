## Pima Indians Diabetes Dataset Analysis

### Project Overview
This project performs Exploratory Data Analysis (EDA) on the **Pima Indians Diabetes Dataset**, which contains medical diagnostic data for 768 female patients of Pima Indian heritage. The objective of the analysis is to identify patterns and relationships between various medical measurements and the likelihood of diabetes onset.

### Dataset Description
The dataset includes the following attributes:
- **Pregnancies:** Number of pregnancies.
- **Glucose:** Plasma glucose concentration.
- **BloodPressure:** Diastolic blood pressure (mm Hg).
- **SkinThickness:** Triceps skinfold thickness (mm).
- **Insulin:** 2-Hour serum insulin (mu U/ml).
- **BMI:** Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction:** A function that represents diabetes pedigree.
- **Age:** Age of the patient.
- **Outcome:** Diabetes diagnosis (1 = Diabetes, 0 = No Diabetes).

## Key Steps in the Analysis
1. **Data Cleaning:**  
   - Replaced invalid zero values in `Glucose`, `BloodPressure`, `SkinThickness`, and `BMI` with their respective column means.

2. **Univariate and Bivariate Analysis:**  
   - Analyzed the distribution of individual features.
   - Identified patterns using scatter plots, box plots, and count plots.

3. **Correlation Analysis:**  
   - Explored relationships between features using a correlation heatmap.
   - Highlighted strong correlations between features like Glucose, BMI, Age, and the Outcome (diabetes diagnosis).

4. **Key Insights:**
   - Higher **Glucose** and **BMI** levels are associated with a higher likelihood of diabetes.
   - Age plays a significant role, with older individuals being more prone to diabetes.
   - Individuals with **BMI** > 25 and **Age** > 27 show an increased risk of diabetes.

#### Installation and Usage
1. Clone the repository.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter notebook for the full EDA process and visualizations.

## Output
- Cleaned dataset: `diabetes1.csv`
- Visual insights and data distributions.
