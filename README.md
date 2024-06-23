# Credit Card Fraud Detection
A fraud detection model is crucial for credit card companies to identify and prevent unauthorized transactions, protecting customers from potential financial losses.


![fraud](https://github.com/Anamika200310/Codsoft/assets/157677070/dbe6ea1b-c561-4231-9414-77cea52ae7e9)

The dataset consists of anonymized credit card transactions made by European cardholders in September 2013, spanning two days. Out of a total of 284,807 transactions, 492 (0.172%) are fraudulent, making the dataset highly imbalanced. The model aims to accurately detect and classify these fraudulent transactions, addressing the significant class imbalance issue.
# Dataset

- **Source:** [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)
- **Description:**
  - The dataset contains only numerical input variables which are the result of a PCA transformation.
  - Features `V1`, `V2`, … `V28` are the principal components obtained with PCA.
  - The features `Time` and `Amount` have not been transformed with PCA:
    - `Time`: Contains the seconds elapsed between each transaction and the first transaction in the dataset.
    - `Amount`: The transaction amount, which can be used for example-dependent cost-sensitive learning.
  - `Class`: The response variable, taking value 1 in case of fraud and 0 otherwise.

# Requirements

To run the analysis and models, the following Python libraries are required:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the necessary packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
# Conclusion

This dataset is useful for building models to detect fraudulent transactions. Due to the highly unbalanced nature of the data, appropriate evaluation metrics such as AUPRC should be used. Visualization of the data can provide insights into the distribution and characteristics of fraudulent vs legitimate transactions.
