# Seaborn Python Data Visualization

A comprehensive exploration of data visualization techniques using **Seaborn** and Python with the California Housing dataset.

## 📊 Project Overview

This project demonstrates various data visualization and exploratory data analysis (EDA) techniques using the popular Seaborn library in Python. The analysis is performed on the California Housing dataset, which contains housing information for various districts in California.

## 📁 Dataset

**Dataset Name:** California Housing Prices

**Source:** [Kaggle - California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download)

**File:** `housing.csv`

### Dataset Features

The California Housing dataset includes the following features:

- **longitude** - Longitude coordinate of the location
- **latitude** - Latitude coordinate of the location
- **housing_median_age** - Median age of houses in the block
- **total_rooms** - Total number of rooms in the block
- **total_bedrooms** - Total number of bedrooms in the block
- **population** - Population in the block
- **households** - Number of households in the block
- **median_income** - Median income of households in the block
- **median_house_value** - Median house value (target variable)
- **ocean_proximity** - Proximity to the ocean

## 🚀 Getting Started

### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install pandas numpy seaborn matplotlib jupyter
```

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tanishanand548/seaborn_py.git
   cd seaborn_py
   ```

2. **Download the dataset:**
   - Visit [Kaggle - California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download)
   - Download the `housing.csv` file
   - Place it in the project root directory

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebooks:**
   ```bash
   jupyter notebook
   ```

## 📚 Contents

This repository contains Jupyter Notebooks (.ipynb files) that showcase:

- **Data Loading & Exploration** - Initial dataset inspection and summary statistics
- **Data Cleaning** - Handling missing values and data preprocessing
- **Univariate Analysis** - Distribution of individual variables
- **Bivariate Analysis** - Relationships between pairs of variables
- **Multivariate Analysis** - Complex relationships among multiple variables
- **Statistical Visualizations** - Using Seaborn's statistical estimation tools
- **Correlation Analysis** - Understanding feature relationships

## 📊 Visualizations Included

The notebooks demonstrate various Seaborn plot types:

- `scatterplot()` - Scatter plots for relationships between variables
- `histplot()` - Histograms and distribution plots
- `kdeplot()` - Kernel density estimation plots
- `boxplot()` - Box plots for distribution comparison
- `violinplot()` - Violin plots showing distribution shape
- `heatmap()` - Correlation matrices and 2D distributions
- `pairplot()` - Pairwise relationships across the dataset
- `regplot()` & `lmplot()` - Regression plots with confidence intervals
- `countplot()` - Categorical data visualization
- `relplot()` - Relationship plots with multiple dimensions

## 🔍 Key Insights & Analysis

The notebooks explore:

1. **Geographical Distribution** - How housing prices vary by location
2. **Price Relationships** - Impact of various features on median house value
3. **Population Patterns** - Distribution of population and density across districts
4. **Income Correlation** - Strong relationship between median income and house prices
5. **Age Analysis** - Influence of housing age on values
6. **Proximity Effects** - Impact of ocean proximity on housing prices

## 💻 Technologies Used

- **Python 3.x** - Programming language
- **Jupyter Notebook** - Interactive computing environment
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Seaborn** - Statistical data visualization
- **Matplotlib** - Plotting and visualization

## 📋 Requirements

```
pandas>=1.0.0
numpy>=1.18.0
seaborn>=0.11.0
matplotlib>=3.2.0
jupyter>=1.0.0
```

## 🛠️ How to Use

1. Open the Jupyter Notebooks in your browser
2. Execute cells to see visualizations and analysis
3. Modify code and parameters to explore different aspects of the data
4. Experiment with different Seaborn functions and styling options

## 📖 Learning Outcomes

By exploring this repository, you will learn:

- How to load and explore datasets using Pandas
- Creating professional statistical visualizations with Seaborn
- Understanding data distributions and relationships
- Performing exploratory data analysis (EDA)
- Customizing plot aesthetics and themes
- Working with Jupyter Notebooks for interactive analysis

## 📝 Notes

- Ensure the `housing.csv` file is placed in the correct directory
- The analysis assumes familiarity with Python and basic statistics
- All visualizations are created using Seaborn's high-level interface built on Matplotlib

## 🤝 Contributing

Feel free to fork this repository, add improvements, or create issues if you have suggestions.

## 📄 License

This project is open source and available under the MIT License.

## 🔗 References

- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Kaggle Dataset Link](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download)

## ✨ Acknowledgments

- California Housing dataset provided by [Kaggle](https://www.kaggle.com/)
- Seaborn library developed by the Python data science community

---

**Last Updated:** May 18, 2026

**Author:** [@tanishanand548](https://github.com/tanishanand548)
