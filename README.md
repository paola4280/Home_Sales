# Home_Sales
This is a Big Data with SparkSQL applications challenge

The objective of this project is to perform data analysis and optimization on a home sales dataset using Apache Spark. The project involves creating a Spark DataFrame from the dataset and transforming it into a temporary table. Various SQL queries are then written to calculate the average price of homes based on different criteria, such as the number of bedrooms, bathrooms, and square footage, as well as average prices by “view” rating with specific conditions. Performance optimization is also emphasized by caching the temporary table and comparing the run time of queries before and after caching. Additionally, partitioning the dataset by the “date_built” field and reading the formatted Parquet data are included in the project, followed by re-running queries on the partitioned data to assess performance. Finally, the temporary table is uncached and verified. The project demonstrates key skills in data manipulation, querying, and performance tuning using Apache Spark.

Home_sales_starter_code_colab is the name of the file with the code, and it's a Google collaboration document. If you have problems viewing the document, here is the direct link to the file: https://colab.research.google.com/drive/1ZbRhuOm3ZDR08LjtT5wOkap9P8jLl8Xx?usp=sharing.

For support, I mostly used class notes, and for debugging, I used AI tools like ChatGPT, particularly for the "cache" section.
