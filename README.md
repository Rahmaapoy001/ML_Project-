# Practical Machine Learning - Course Project

## 🔍 Project Objective

Using accelerometer data from wearable devices, this project aims to predict the manner in which participants performed weight lifting exercises. The main target variable is `classe`, which categorizes different exercise techniques (both correct and incorrect).

## 🧠 Approach

- The dataset was cleaned by removing columns with mostly missing values and irrelevant identifiers.
- Data was split into training and testing sets.
- A **Random Forest** model was trained using 5-fold cross-validation.
- The model was evaluated using accuracy and a confusion matrix.
- Final predictions were made on a separate test dataset of 20 cases.

## 📁 Files

- `Practical-machine-learning.Rmd`: Full R Markdown file containing:
  - Data preprocessing steps
  - Model training and cross-validation
  - Prediction results
  - Summary and conclusion

## 📊 Results

- The Random Forest model achieved high accuracy on the validation set.
- The final model was used to generate predictions for the test dataset required by the Course Project Prediction Quiz.

## 📌 How to View

To view the analysis:
1. Download the `.Rmd` file from this repo.
2. Open it in **RStudio**.
3. Click **Knit → Knit to HTML** to generate and view the report.

---

Thanks for reviewing! 🙏
