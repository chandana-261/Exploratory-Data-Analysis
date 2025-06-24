# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Objective
The goal of this task is to understand the Titanic dataset using statistical summaries and visualizations to uncover insights such as trends, patterns, correlations, and anomalies.

## 🧰 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## 📊 Task Overview

 ✅ 1. Summary Statistics
We computed basic statistics like mean, median, standard deviation, min, max, and quartiles for numeric features using `df.describe()`.

✅ 2. Histograms
Visualized the distribution of numeric features: `Age`, `Fare`, `SibSp`, and `Parch` using histograms and KDE plots.

 ✅ 3. Boxplots
Displayed boxplots to identify outliers and visualize spread in the numeric features.

 ✅ 4. Correlation Heatmap
Created a heatmap to examine correlation between numeric features such as `Age`, `Fare`, `SibSp`, `Parch`, and `Survived`.

 ✅ 5. Pairplot
Visualized pairwise relationships between selected features colored by the `Survived` outcome to understand patterns and groupings.

📁 Files Generated
- `histograms.png`
- `boxplots.png`
- `correlation_heatmap.png`
- `pairplot.png`
- `eda_titanic.py` (analysis code)

## 🧪 How to Run
1. Clone this repo or upload the files to your working directory.
2. Ensure you have the required libraries:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3. Run the analysis:
    ```bash
    python eda_titanic.py
    ```
4. Check the output `.png` files for visual insights.

## 📬 Dataset
Dataset used: [Titanic-Dataset.csv](./Titanic-Dataset.csv)

## 📈 Insights Observed
- Strong class imbalance in `Survived` (more non-survivors).
- Positive correlation between `Fare` and `Pclass` (wealthier = higher class).
- `Age` and `Fare` have some outliers.
- Survival is associated with lower `SibSp` and `Parch`.

## 🙌 Contributions
Project by: LAKSHMI CHANDANA YANAMANDRA

## 📄 License
This project is open-source and available under the MIT License.
