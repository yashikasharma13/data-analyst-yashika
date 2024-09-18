# data-analyst-yashika
Objective:  
The main objective is to clean, transform, and consolidate data from various sources to create a comprehensive, accurate dataset. This dataset will help in customer analytics and enhance Company’s ability to derive actionable insights for marketing strategies and decision-making.
Background:  
Company collects customer data through multiple channels such as sales transactions, customer service interactions, and marketing campaigns. However, this data is often fragmented, inconsistent, and incomplete, which hampers data analysis and strategy development. This project focuses on addressing these data issues through effective data wrangling techniques.
Dataset Overview:
Sales Data: Transaction records, including customer IDs, product details, purchase amounts, and timestamps.
Customer Information: Customer demographics like age, gender, location, and account creation date.
Customer Service Records: Logs of customer inquiries, complaints, and resolutions.
Marketing Interaction Data: Data on campaign performance (e.g., email open rates, click-through rates).
Methodology
1. Data Collection:
Answer: In this step, datasets are gathered from multiple internal systems (e.g., CRM systems, databases) and third-party platforms (e.g., marketing platforms). You should ensure that all relevant customer-related data is identified to build a comprehensive customer profile.
2. Data Assessment:
Answer: Assess data quality by identifying missing values, duplicate entries, and inconsistencies across datasets. This includes documenting any discrepancies in formats, such as mismatched customer IDs, or missing demographic data.
3. Data Cleaning:
Answer: Handle missing data appropriately (either by imputing or excluding based on relevance). Remove any duplicate records (especially common in customer service logs or transaction data). Correct data format inconsistencies (e.g., standardizing date formats or naming conventions). Normalize categorical variables, such as standardizing customer status across datasets to ensure consistent terminology.
4. Data Transformation:
Answer: Convert data types where necessary (e.g., strings to datetime objects). Derive new features to support analytics, such as total purchase amounts or frequency of transactions. Aggregate data at the right level (e.g., monthly customer sales) for more meaningful analysis.
5. Data Consolidation:
Answer: Merge datasets into a unified customer database using unique identifiers like customer IDs. Ensure that each customer’s journey (sales, marketing, and service interactions) is accurately represented to provide a full customer profile.
6. Documentation and Validation:
Answer: Document the entire data wrangling process, including data sources, methods used for cleaning and transformations, and any issues encountered. Perform exploratory data analysis (EDA) to validate that the cleaned data is accurate, complete, and ready for analysis. This includes visualizing key variables to confirm the data’s integrity.
Tools and Technologies:
We used AWS Glue DataBrew for all the steps
But we can also use Python (using Pandas and NumPy) or R for data cleaning and manipulation.
SQL for extracting and assessing data from relational databases.
Jupyter Notebook or RStudio for interactive data wrangling.
Visualization Tools like Matplotlib or Seaborn to support exploratory data analysis (EDA).
Deliverables:
1. Cleaned Dataset: A unified and clean dataset in a format like CSV or Excel, ready for further analysis.
2. Comprehensive Report: A detailed report on the data wrangling process, including the methods used, challenges encountered, and final dataset characteristics.
3. Visualizations: Visualizations that confirm the dataset's quality and illustrate key insights uncovered during EDA.
Timeline:
It took us an hour to do the project with AWS DataBrew
Conclusion:  
This data wrangling project is crucial for creating a robust, accurate dataset that will drive Company’s customer analytics efforts. It will enable more targeted marketing, improved customer service, and informed decision-making, contributing to the company’s overall growth.

