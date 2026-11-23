# Survival Analysis Learning Report

A course project for SUSTech's [STA323 Big Data Analysis Software and Application (Hadoop or Spark)](https://mirrors.sustech.edu.cn/courses/syllabus/STA323.pdf). The project analyzes MACCDC network logs with Spark SQL and reproduces the [Databricks survival analysis of customer churn and lifetime value](https://www.databricks.com/solutions/accelerators/survival-analysis-for-churn-and-lifetime-value).

## Read or reproduce

Start with the [report](report.pdf). Open the [Q1 notebook](project1/Q1/project.ipynb) in Spark and set `MACCDC_DATA_DIR` to the MACCDC input directory. For the [Q2 notebook](project1/Q2/codes.ipynb), download [IBM's `Telco-Customer-Churn.csv`](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv) and set `TELCO_DATA_DIR` to the directory containing it. Q2 validates the CSV headers and builds its bronze and silver views in the current Spark session. The notebooks are distributed with their saved outputs cleared.
