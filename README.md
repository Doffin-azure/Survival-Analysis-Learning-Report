# Survival Analysis Learning Report

A SUSTech Big Data coursework project using Spark to reproduce a survival analysis of customer churn and lifetime value. It follows the [Databricks solution accelerator](https://www.databricks.com/solutions/accelerators/survival-analysis-for-churn-and-lifetime-value).

## Read or reproduce

Start with the [report](report.pdf). Open the [Q1 notebook](project1/Q1/project.ipynb) in Spark and set `MACCDC_DATA_DIR` to the MACCDC input directory. For the [Q2 notebook](project1/Q2/codes.ipynb), set `TELCO_DATA_DIR` to the directory containing `Telco-Customer-Churn.csv`. Q2 builds its bronze and silver views in the current Spark session and reads the input CSV in place. The notebooks are distributed with their saved outputs cleared.
