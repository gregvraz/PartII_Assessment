# PartII_Assessment
customer_segmentation_problem

Please make sure that you have downloaded and stored at the same location both the Customer_Segmentation_Assessment_Part II.ipynb and the csv file bq_results_orders_jan2021.csv

Due to permission issues, I could not connect on the SQL database via the API. Therefore, I executed the following query and saved the CSV with all the available data locally.

SELECT *
FROM `bi-2019-test.ad_hoc.orders_jan2021`;

For the purpose of this assessment, I used Python version 3.8.3 in conda version 4.10.3

Please make sure that you have the latest version of the following libraries installed in your machine:
- pandas
- numpy
- datetime
- seaborn
- matplotlib.pyplot
- squarify
