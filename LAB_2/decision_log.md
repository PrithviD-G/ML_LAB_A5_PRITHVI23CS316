# Decision Log – Titanic Dataset

1. **Data Loading**
- Original Shape: (891, 12)

2. **EDA**
- df.info(), df.describe(), heatmaps
- Countplots for categorical variables

3. **Missing Value Handling**
- Columns with missing: ['Age', 'Cabin', 'Embarked']
- Missing flags created for Age, Cabin, Embarked
- Imputation strategy:
  - Age: Median per Pclass + Sex
  - Embarked: Mode
  - Cabin: 'Unknown' + Deck extraction

4. **Outlier Treatment**
- Column: Fare
- Method: IQR capping
- Range: [-26.724, 65.6344]

5. **Final Shape**
- (891, 16)
