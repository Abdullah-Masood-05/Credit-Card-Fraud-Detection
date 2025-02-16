# Credit Card Fraud Detection

This project is focused on detecting fraudulent credit card transactions using Logistic Regression. The dataset is sourced from Kaggle and contains anonymized credit card transactions labeled as fraudulent or legitimate.

## Dataset

The dataset used is **[Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)** from Kaggle. It contains transactions made by European cardholders in September 2013, with a total of 284,807 transactions, out of which 492 are fraudulent.

### How to Download the Dataset

1. Go to the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) on Kaggle.
2. Click on "Download" to get the `creditcard.csv` file.
3. Place the downloaded `creditcard.csv` file in the root directory of this project.

## Project Structure

- **main.ipynb**: Jupyter Notebook containing the full data analysis, preprocessing, model building, and evaluation.
- **creditcard.csv**: (Not included) Dataset to be downloaded from Kaggle as per the instructions above.

## Installation Requirements

To run this notebook, you need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt`, you can create one with the following content:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/Abdullah-Masood-05/Credit-Card-Fraud-Detection.git
```

2. Navigate to the project directory:

```bash
cd Credit-Card-Fraud-Detection
```

3. Ensure the dataset is in the root folder.

4. Launch Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```

5. Run the notebook cells sequentially to see the data cleaning, preprocessing, model building, and evaluation steps.

## Model Details

- **Algorithm**: Logistic Regression
- **Objective**: Classify transactions as fraudulent or legitimate.
- **Metrics Used**:
  - Classification Report
  - Confusion Matrix

## Results and Evaluation

The model's performance is evaluated using standard classification metrics like precision, recall, F1-score, and accuracy, along with a confusion matrix to understand false positives and false negatives.

## Contributors

- [Abdullah Masood](https://github.com/Abdullah-Masood-05)

## License

This project is licensed under the MIT License.

---