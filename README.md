# Climate Informatics Project

## Overview
This project focuses on analyzing climate data using various Python libraries and machine learning techniques. It processes historical climate data, identifies extreme events, and makes future predictions using the Prophet forecasting model.

## Features
- Data preprocessing and cleaning
- Time series analysis
- Extreme event detection
- Future climate trend predictions
- Data visualization

## Dependencies
This project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn
- yellowbrick
- statsmodels
- prophet
- ipywidgets
- jupyter

ClimateInformatics/
│
├── data/
│   ├── data9724.csv.gz
│   └── variable_descriptions.csv
│
├── src/
│   └── notebooks/
│       └── dataanalysis.ipynb
│
├── images/
│   ├── TAR_sample.png
│   ├── TAR_mean.png
│   ├── UR_sample.png
│   ├── UR_mean.png
│   ├── CHUVA_sample.png
│   └── CHUVA_mean.png
│
└── README.md

## Usage

1. Ensure all dependencies are installed.

2. Open the dataanalysis.ipynb notebook in Jupyter.
3. Run the cells in order to perform the analysis.

## Data Description

- data9724.csv.gz: Main dataset containing climate variables.
- variable_descriptions.csv: Descriptions of the variables used in the analysis.

## Output
- CSV files with annual frequency of extreme events for each climate variable.
- PNG images of time series plots and forecasts for each variable.
## Analysis Process
1. Data loading and preprocessing
2. Outlier removal
3. Time series resampling
4. Prophet model fitting
5. Extreme event identification
6. Future trend prediction
7. Data visualization

## Contributing
Feel free to fork this project and submit pull requests with improvements or bug fixes.

## License
[MIT]

Contact
[adsonnalves@gmail.com]

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib xlrd openpyxl scikit-learn seaborn yellowbrick statsmodels prophet ipywidgets jupyter


