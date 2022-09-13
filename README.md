# Food-Demand-Forecast
Analytics Vidhya competition

FOOD DEMAND FORECAST

CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation

INTRODUCTION
------------

The Food Demand Forecast project applies data science and machine learning techniques to try to predict the number of food orders for each meal at each distribution center in the next 10 weeks

Problem statement: (https://datahack.analyticsvidhya.com/contest/genpact-machine-learning-hackathon-1/#ProblemStatement)

Project files/ folder:
 * Notebook/source code: Food_Demand_Forecast.ipynb
 * Data folder: Food Data
  ** Source data files: train.csv, test.csv, fulfilment_center_info.csv, meal_info.csv
  ** Project output files: submission.csv, history_models.csv, model_best
 * Reporting file: Report.pptx
 * README.md

Follow the below contents to set up and run the project successfully.

REQUIREMENTS
------------

 * Language: [Python 3](https://www.python.org/downloads/)
 * Environment: [Google Colab](https://colab.research.google.com/)
 * Package/ Library: pandas, numpy, scikit learn, matplotlib, seaborn
 * Machine learning framework: xgboost, lightgbm, catboost
 
  ** Note: a Google account is required

INSTALLATION
------------

1. Open file "Food_Demand_Forecast.ipynb" within Google Colab via any web browser.

2. GPU configuration
 * Connect notebook to GPU (https://colab.research.google.com/notebooks/gpu.ipynb)
 * In case GPU is not available, the project can be run on CPU by commenting out 02 code lines 
   associating with the comment "#turn on if gpu is available for more speed"

3. Prepare data source
 * Upload the "Food Data" folder to the Google Drive account which you used for logging in 
   Google Colab
 * In case you upload the folder to a different position, make sure to adjust the folder path
   accordingly by correcting the "path" variable (default path: '/content/drive/MyDrive/Food Data/')

4. Run the notebook
 * Runtime/ Run all
 * Connect to Google Drive

5. (Optional) Install any missing required Package/ Library/ Framework
 * Run the following code lines within your notebook: !pip install <package_name> 
 * E.g !pip install pandas
 * Run the remaining lines or re-run the entire notebook
