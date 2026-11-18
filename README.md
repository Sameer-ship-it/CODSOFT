# CodSoft Machine Learning Internship Projects

A collection of three Jupyter notebooks exploring supervised learning and text classification as part of a CodSoft internship.

## Projects

| Notebook | Topic | Techniques explored |
| --- | --- | --- |
| `TSK1.ipynb` | Customer churn prediction | Categorical encoding, train/test split, scaling, Logistic Regression, Random Forest, and XGBoost |
| `TSK2.ipynb` | Credit-card fraud classification | Categorical encoding, feature scaling, Logistic Regression, Decision Tree, and Random Forest |
| `TSK3.ipynb` | SMS spam classification | TF-IDF features with Multinomial Naive Bayes and Logistic Regression |

These notebooks are experiments for learning and comparison. Their results depend on the datasets and the preprocessing choices in each notebook.

## Data

The notebooks expect datasets that are not stored in this repository. Some cells refer to files in a local Windows Downloads folder. Download a dataset you are authorized to use, update the relevant `read_csv` path, and avoid committing private or licensed data.

## Run the notebooks

```bash
git clone https://github.com/Sameer-ship-it/CODSOFT.git
cd CODSOFT
python -m venv .venv
```

Activate the environment, then install Jupyter and the libraries used by the notebooks:

```bash
# Windows PowerShell
.venv\Scripts\Activate.ps1
# macOS / Linux
source .venv/bin/activate
```

```bash
python -m pip install jupyter pandas numpy scikit-learn matplotlib seaborn xgboost category-encoders
jupyter notebook
```

Open a notebook and run its cells after configuring the dataset path. Notebooks may need package or data-path adjustments for your environment.

## Notes

- The work is educational and is not a production fraud, churn, or messaging detection service.
- For imbalanced classification, review precision, recall, F1 score, and the confusion matrix rather than relying on accuracy alone.
- Review dataset licenses and remove personal identifiers before sharing data.

## Author

[Sameer Raza](https://github.com/Sameer-ship-it)
