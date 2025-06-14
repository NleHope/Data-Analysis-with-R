# Data-Analysis-with-R
# Body Performance Data Analysis

## 📄 Description
This project explores a real-world dataset related to body performance metrics collected from 13,393 individuals in South Korea, spanning different age groups and genders. The goal is to determine which physical attributes most influence exercise performance and to evaluate various classification models to predict performance classes (A to D).

## 🧠 Features (Variables)
The dataset `bodyPerformance.csv` includes the following 12 features:

- `age`: Age of individual (20–64 years)
- `gender`: Gender (F = female, M = male)
- `height_cm`: Height in centimeters
- `weight_kg`: Weight in kilograms
- `body_fat_%`: Body fat percentage
- `diastolic`: Diastolic blood pressure
- `systolic`: Systolic blood pressure
- `gripForce`: Grip strength
- `sit and bend forward_cm`: Flexibility test result
- `sit-ups counts`: Number of sit-ups
- `broad jump_cm`: Broad jump distance in centimeters
- `class`: Performance classification (A = best, B, C, D)

## 🧪 Methods
We applied the following analysis and modeling techniques:
- **Exploratory Data Analysis (EDA)**: Outlier handling, correlation matrix, and boxplots
- **Statistical Testing**: ANOVA to assess differences across performance classes
- **Classification Models**:
  - Multinomial Logistic Regression
  - Linear Discriminant Analysis (LDA)
  - Quadratic Discriminant Analysis (QDA)
  - Random Forest

## 👥 Team Members
- Phạm Bá Hoàng Anh – 22280003
- Nguyễn Minh Đạt – 22280009
- Lư Xuân Dương – 22280015
- Nguyễn Đức Hiệp – 22280022
- **Lê Trọng Nghĩa – 22280059**

## ✅ Results & Conclusion

- The **Random Forest** model outperformed others, achieving an **accuracy of 74.17%** and showing balanced performance across classes.
- The most influential features for predicting performance are:
  - `sit_ups_counts`
  - `broad_jump_cm`
  - `age`
- Features such as `diastolic`, `systolic`, `height_cm`, `body_fat`, and `gender` showed minimal impact and were removed in later iterations to simplify the model.
- Practical takeaway: Since `age` is non-modifiable, improvements in performance should focus on exercises that boost `sit-up counts` and `broad jump` distance.

---

