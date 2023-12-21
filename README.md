# UK Greenhouse Gas Emissions Analysis and Forecasting

## Overview

This repository contains code and documentation for analyzing and forecasting greenhouse gas (GHG) emissions in the UK. The project aims to assess the UK's progress towards its net-zero emissions target by 2050. The analysis covers data from the ONS atmospheric emissions dataset, providing insights into historical trends and predicting future emissions.

## Project Structure

- **data:** Contains the raw data file, typically named `atmoshpericemissionsghg.xlsx`.
- **notebooks:** Jupyter notebooks containing data cleaning, exploratory data analysis, and model building.
- **images:** Images and visualizations generated during the analysis.
- **scripts:** Python scripts for data cleaning, model training, and other functionalities.

## Results and Insights
- Detailed insights and analysis results are presented in the project report.
- Key findings include a consistent GHG decrease since 1990 and the impact of legislative changes in 2019.

## Model Details
- PyCaret was used for model selection and forecasting.
- The ETS model emerged as the best performer, achieving high accuracy.
- Compared ETS model with Linear Regression model
- For detailed model performance, refer to the project report.

## Future Improvements
- Enhancements to the ETS model, including incorporating additional variables and exploring ensemble methods.
- Further exploration of seasonality timestamps for improved prediction accuracy.
