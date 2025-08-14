# Data Card – Titanic Dataset

**Filename:** Titanic-Dataset.csv  
**Rows before cleaning:** 891  
**Rows after cleaning:** 891  
**Columns:** 16  

## Columns & Missing Values
| Column | Data Type | Missing Values | Imputation/Notes |
|--------|-----------|----------------|----------------|
| PassengerId | int64 | 0 | None |
| Survived | int64 | 0 | None |
| Pclass | int64 | 0 | None |
| Name | object | 0 | None |
| Sex | object | 0 | None |
| Age | float64 | 177 | Median per Pclass+Sex |
| SibSp | int64 | 0 | None |
| Parch | int64 | 0 | None |
| Ticket | object | 0 | None |
| Fare | float64 | 0 | None |
| Cabin | object | 687 | Filled 'Unknown', extracted Deck |
| Embarked | object | 2 | Mode |
| Age_MissingFlag | int64 | 0 | None |
| Cabin_MissingFlag | int64 | 0 | None |
| Embarked_MissingFlag | int64 | 0 | None |
| Deck | object | 0 | None |

## Notes
- Dataset ready for modeling.
- Missing flags can be used as features.
