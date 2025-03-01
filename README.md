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
- **Google Colab**: For running the notebook in a cloud environment.
- **Python**: The primary programming language for analysis.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn (if applicable)**: For potential clustering or predictive modeling.

## How to Run in Google Colab
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Upload the dataset `winemag-data-130k-v2.csv` to your Google Drive.
3. Mount Google Drive in the Colab notebook using:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Load the dataset from Google Drive:
   ```python
   import pandas as pd
   df = pd.read_csv('/content/drive/My Drive/winemag-data-130k-v2.csv')
   ```
5. Run all cells in the notebook to process and analyze the dataset.

## Expected Insights
- Price vs. quality relationships.
- Countries with the highest-rated wines.
- Most popular wine varieties based on user reviews.
- Trends in wine ratings across different regions.

## Acknowledgments
Dataset source: [Kaggle](https://www.kaggle.com/datasets)

## License
This project is for educational and analytical purposes only.
