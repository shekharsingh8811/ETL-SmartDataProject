# ETL-SmartDataProject
This project consists of three steps as mentioned below.


Step 1: Deducing the question
- Dataset used is 'Product_Sales_Data.csv'. 
-	Profiled the dataset 'Product_Sales_Data' to find relevant and appropriate questions that can be answered using any of the data analytics techniques.
-	Came up with three questions as follows:
    1. Considering total purchase amount, classify customers into 3 categories (High, Mid or Low).
    2. Classify employees into 3 bonus categories (3% Bonus, 2% Bonus, 1% Bonus) based on the total count & amount of sale provided.
    3. Explore co-relations between employee, customers and products.

Step 2: ETL Workflow
-	Designed and implemented an ETL workflow using Python programming language.
-	Any data quality steps necessary for curating/transforming the data is a part of the workflow, i.e., they are automated and not performed manually external to the primary ETL workflow.
-	The result of the ETL workflow is a Start schema containing a Fact table and three Dimension tables. 
- 'ProductSalesData_ETL_Process.ipynb' python notebook has all the related steps.

Step 3: Data Analytics
-	Applied data analytics techniques using Python programming language.
-	Used the ETL results generated in Step 2 and applied the appropriate data analytics technique to answer questions that had been proposed in Step 1.
- 'ProductSalesData_Analysis_Visualisation.ipynb' python notebook has all the related analysis and visualization.
