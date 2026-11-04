# Superstore Sales & Profitability Analysis

## Project Overview
This project explores the Sample Superstore dataset to understand sales and profitability across product categories, subcategories, regions, customer segments, discount levels, shipping modes, and time.

The goal is to identify business performance patterns, highlight areas of low profitability, and provide data-driven recommendations.

## Objectives
- Analyze sales and profit across categories and regions.
- Identify profitable and loss-making product subcategories.
- Examine the relationship between discount levels and profitability.
- Compare customer segments and shipping modes.
- Explore monthly sales and profit trends.
- Present actionable business recommendations.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Findings
- Technology generated the highest category sales and total profit.
- Furniture generated substantial sales but comparatively low profit.
- The West region recorded the highest sales and total profit.
- The Central region had the lowest aggregate profit margin.
- Consumer customers contributed the highest sales and total profit.
- Home Office recorded the highest segment profit margin.
- Discount levels up to 20% were associated with positive aggregate profit, while discount levels of 30% and above were associated with losses.
- December 2016 was the most profitable month, while January 2015 recorded the lowest monthly profit.

## Recommendations
- Review high-discount policies, particularly for loss-making product combinations.
- Investigate the profitability of Tables, Bookcases, and other loss-making subcategories.
- Monitor regional performance using both sales and profit margin.
- Track profitability alongside sales volume.
- Investigate factors behind monthly profit fluctuations.

## Project Structure
```text
01_Sales_Analytics/
├── notebooks/
│   └── 01_EDA.ipynb
├── Data/
│   └── Superstore.csv  # Dataset kept locally; not included in GitHub
├── README.md
└── .gitignore
```

## Dataset
The dataset is not included in this repository. To run the notebook, obtain the Sample Superstore dataset separately and place the CSV file in the `Data` folder.

The notebook loads it using a relative path:

```python
df = pd.read_csv("../Data/Superstore.csv", encoding="latin1")
```

## How to Run
1. Clone or download this repository.
2. Obtain the dataset separately and place it in the `Data` folder.
3. Open `notebooks/01_EDA.ipynb` in Jupyter Notebook.
4. Run the notebook cells from top to bottom.

## Notes
This project is exploratory. Observed relationships—such as discount levels and losses—show associations and do not by themselves establish causation.

