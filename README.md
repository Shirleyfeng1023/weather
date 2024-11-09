# World Weather Analysis Project

## Project Overview
The goal of this project is to analyze global weather data to identify trends, patterns, and relationships among various weather parameters across continents and regions. The dataset used provides daily weather data from May 16 - August 2, 2024, and includes over 40 features such as temperature, wind speed, air pressure, humidity, visibility, and air quality measurements. This analysis was conducted for the World Meteorological Organization to better understand global climate conditions and their variations.

### Dataset
The dataset used can be found [here](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository) and covers weather data for capital cities worldwide.

## Methodology
### Data Collection and Preprocessing
1. **Data Collection**: The dataset contains daily weather records from May 16 - August 2, 2024, covering 210 countries and 247 unique locations.
2. **Preprocessing**:
   - **Handling Inconsistencies/Duplicates**: Identifying and removing redundant data entries.
   - **Handling Missing Values**: Addressing missing data to ensure completeness.
   - **Handling Outliers**: Outliers were detected and managed through various statistical techniques.
3. **Data Cleaning**: Columns that did not contribute to the analysis, such as `last_updated_epoch`, were removed to enhance data clarity.

### Exploratory Data Analysis (EDA)
The EDA was conducted to understand data distribution and relationships:
1. **Data Granularity and Imbalance**: Analyzed the distribution of data across dates and locations.
2. **Univariate Analysis**: Assessed individual metrics like temperature and latitude to identify skewness and distribution characteristics.
3. **Bivariate Analysis**: Explored relationships between metrics, such as the correlation between air quality and temperature, using scatterplots and other visualization methods.
4. **Time Trend Analysis**: Analyzed weather feature trends over daily and weekly intervals.

## Results
- **Data Distribution**: Insights into data imbalance, with some dates recording as many as 378 instances of weather data while others had as few as 6.
- **Trends and Correlations**: Key findings on geographical and temporal weather patterns, including potential biases in data distribution due to geographic concentration.
- **Visualizations**: Graphical representations of distributions, trends, and relationships among various weather parameters.


## How to Use
### Prerequisites
To run this analysis, you will need:
- Python 3.x
- Jupyter Notebook
- The following libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`

### Instructions
Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook weather.ipynb
   ```
