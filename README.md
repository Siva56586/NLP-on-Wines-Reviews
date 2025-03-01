# Wine Reviews Analysis

## Project Overview
This project is focused on analyzing a dataset of wine reviews to derive meaningful insights. By leveraging data processing and visualization techniques, we explore trends in wine ratings, prices, and regional preferences.

## Dataset
The dataset used in this project, `winemag-data-130k-v2.csv`, contains over 130,000 wine reviews. Each entry includes:
- **Country**: The country where the wine was produced
- **Designation**: The specific name of the wine
- **Points**: The rating score assigned to the wine
- **Price**: The cost of the wine
- **Province**: The region within the country
- **Region_1, Region_2**: Sub-regions of wine production
- **Variety**: The type of grape used in the wine
- **Winery**: The name of the wine producer
- **Description**: A short review of the wine

## Objectives
- Perform **data cleaning and preprocessing** to handle missing values and inconsistencies.
- Conduct **exploratory data analysis (EDA)** to uncover trends in wine reviews.
- Utilize **data visualization** techniques to display insights into wine quality, price distribution, and regional preferences.
- Identify **top-rated wines** based on ratings and affordability.

## Technologies Used
This project is implemented using the following technologies:
- **Python**: The primary programming language for analysis.
- **Jupyter Notebook**: For interactive data exploration.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn (if applicable)**: For potential clustering or predictive modeling.

## Installation & Setup
To set up the environment, install the required dependencies using pip:
```bash
pip install numpy pandas matplotlib seaborn
```
Clone the repository and navigate to the project folder:
```bash
git clone <repository_url>
cd wine-reviews-analysis
```
Ensure the dataset `winemag-data-130k-v2.csv` is placed in the correct directory before running the Jupyter Notebook.

## Usage
1. Open Jupyter Notebook:
```bash
jupyter notebook
```
2. Load the notebook and run the cells step by step to process and analyze the dataset.
3. Visualizations and insights will be displayed within the notebook.

## Expected Insights
- Price vs. quality relationships.
- Countries with the highest-rated wines.
- Most popular wine varieties based on user reviews.
- Trends in wine ratings across different regions.

## Acknowledgments
Dataset source: [Kaggle](https://www.kaggle.com/datasets)

## License
This project is for educational and analytical purposes only.
