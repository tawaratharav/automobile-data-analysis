# Car Data Analytics using Python

## Overview
This project performs Exploratory Data Analysis (EDA) on the Motor Trend Cars (mtcars) dataset using Python and Pandas. The analysis includes data cleaning, descriptive statistics, correlation analysis, data manipulation, and sorting operations to uncover insights about vehicle performance and fuel efficiency.

## Dataset
The dataset contains information on 32 automobile models from the 1973–74 Motor Trend US magazine.

### Features
- mpg : Miles per gallon
- cyl : Number of cylinders
- disp : Engine displacement
- hp : Gross horsepower
- drat : Rear axle ratio
- wt : Weight
- qsec : Quarter-mile time
- vs : Engine type
- am : Transmission type
- gear : Number of forward gears
- carb : Number of carburetors

## Objectives
- Import and explore the dataset
- Perform descriptive statistical analysis
- Clean and preprocess data
- Handle missing values
- Analyze correlations between variables
- Perform data manipulation using Pandas
- Sort and filter data for insights

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Project Workflow

### 1. Data Import
- Load dataset using Pandas
- Inspect data structure
- View sample records

### 2. Data Exploration
- Dataset dimensions
- Data types
- Summary statistics
- Mean, Median, Standard Deviation

### 3. Data Cleaning
- Rename columns
- Handle missing values
- Convert data types
- Remove unnecessary columns

### 4. Correlation Analysis
- Generate correlation matrix
- Identify strongly correlated features
- Analyze factors affecting fuel efficiency (mpg)

### 5. Data Manipulation
- Indexing using iloc and loc
- Filtering records
- Applying functions
- Updating column values

### 6. Sorting & Analysis
- Sort records by different attributes
- Extract meaningful insights

## Key Insights
- Vehicle weight (wt) has a strong negative correlation with fuel efficiency (mpg).
- Engine displacement (disp) and horsepower (hp) negatively impact fuel economy.
- Manual transmission vehicles tend to have better fuel efficiency.
- Weight is one of the most influential factors affecting MPG.

## Repository Structure

```
car-data-analytics-python/
│
├── data/
│   └── mtcars.csv
│
├── notebooks/
│   └── Car_Data_Analytics.ipynb
│
├── images/
│   └── charts/
│
├── README.md
│
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/car-data-analytics-python.git
```

Navigate to the project directory:

```bash
cd car-data-analytics-python
```

Install dependencies:

```bash
pip install pandas numpy matplotlib
```

## Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

or upload the notebook to Google Colab.

## Future Improvements
- Interactive dashboards using Power BI
- Advanced visualizations with Seaborn
- Predictive modeling for fuel efficiency
- Feature engineering and machine learning

## Author

Atharav Tawar
