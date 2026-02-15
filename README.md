The dataset was processed and transformed using Power Query to ensure structural consistency, data integrity, and analytical readiness. 
Initial preprocessing involved reviewing the schema and reorganizing column order to reflect a logical hierarchical structure (Country → State → City). 
Column names were standardized to improve clarity and maintain naming consistency across the dataset.
Data types were explicitly defined to prevent implicit conversion errors. Date fields (Order Date, Shipping Date) were converted to Date format, while quantitative variables such as Sales, Quantity, and Profit were cast as numeric types to enable accurate aggregation and calculation.
Data validation procedures included filtering invalid entries and removing duplicate records to preserve referential integrity. 
Redundant and non-essential columns were eliminated to optimize model performance and reduce storage overhead.
The final dataset was verified to ensure 0% errors, nulls, and empty values across key analytical fields.
These steps prepared the dataset for robust downstream analysis, DAX calculations, and dashboard visualization within Power BI, ensuring reliable insights into sales trends, profitability, and regional performance.
