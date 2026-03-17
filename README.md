# SQL-Retail-Sales
My first SQL project exploring retail sales data, where I practiced data cleaning, aggregation, and analytical queries to extract meaningful insights.

Retail Sales Analysis (SQL Project)

📌 Overview
This project explores a retail sales dataset using SQL to uncover insights about customer behavior, product performance, and sales trends.
It was built as a hands-on practice project to strengthen my skills in data analysis using SQL, including data cleaning, aggregation, and business-driven querying.

🎯Objectives
1. Build and structure a retail database
2. Clean and validate raw sales data
3. Perform exploratory data analysis (EDA)
4. Answer real-world business questions using SQL

🛠️ Tools & Technologies
- SQL (PostgreSQL / MySQL — adjust to what you used)
- CSV dataset
- SQL queries for analysis

🗂️ Dataset Description
- The dataset contains retail transaction records with fields such as:
- Transaction ID
- Sale date & time
- Customer ID, gender, and age
- Product category
- Quantity, price, and total sales

🧱Database Setup
A database was created to store and manage the retail data.
<img width="772" height="416" alt="image" src="https://github.com/user-attachments/assets/70a00789-c9ae-41ff-a1f2-25a244861912" />

🧹 Data Cleaning
Before analysis, the dataset was checked for:
- Missing or null values
- Incomplete records
- Invalid rows were removed to ensure accurate analysis.
<img width="1148" height="494" alt="image" src="https://github.com/user-attachments/assets/bf4db3ad-0bff-4ee2-aa24-b0a3befa89e0" />
<img width="1136" height="499" alt="image" src="https://github.com/user-attachments/assets/e7fe9234-3ba3-4cb0-83a4-92ba316137f7" />
<img width="1115" height="263" alt="image" src="https://github.com/user-attachments/assets/cbc2a061-7cee-4b6a-aef4-3f47cc6b5e31" />


📊 Analysis Performed
Key Questions are explored:

-- How many sales we have?
<img width="1127" height="38" alt="image" src="https://github.com/user-attachments/assets/5c4f9627-b818-42d1-98a2-8b0b9a6b390f" />

-- How many unique customers we have?
<img width="619" height="55" alt="image" src="https://github.com/user-attachments/assets/b7d2f5cd-776c-49a0-9542-fff17d130c79" />

-- Data analysis and Business Key Problems and Answers

-- Write a SQL query to retrieve all columns for sales made on '2022-11-05:
<img width="375" height="86" alt="image" src="https://github.com/user-attachments/assets/82a03f5d-9a92-4272-b10c-757c8f1059ed" />

-- Write a SQL query to retrieve all transactions where the category is 'Clothing' and the quantity sold is more than 4 in the month of Nov-2022:
<img width="257" height="222" alt="image" src="https://github.com/user-attachments/assets/35d997bd-773f-4742-af86-7013cbd1648d" />

-- Write a SQL query to calculate the total sales (total_sale) for each category.:
<img width="301" height="165" alt="image" src="https://github.com/user-attachments/assets/d274985c-89e4-4fac-bd8d-39a5bf4079c3" />

-- Write a SQL query to find the average age of customers who purchased items from the 'Beauty' category.:
<img width="273" height="112" alt="image" src="https://github.com/user-attachments/assets/d1ced921-2525-4ae0-83ce-0699291e40c6" />

-- Write a SQL query to find all transactions where the total_sale is greater than 1000.:
<img width="249" height="62" alt="image" src="https://github.com/user-attachments/assets/d42cd8f1-ea0c-4176-b357-8d9186651368" />

-- Write a SQL query to find the total number of transactions (transaction_id) made by each gender in each category.:
<img width="256" height="272" alt="image" src="https://github.com/user-attachments/assets/8d202403-6cf1-4fd6-a9b6-b6248bfe1089" />

-- Write a SQL query to calculate the average sale for each month. Find out best selling month in each year:
<img width="499" height="471" alt="image" src="https://github.com/user-attachments/assets/e514f580-af01-48c4-8b62-dde64f75ffed" />

-- **Write a SQL query to find the top 5 customers based on the highest total sales **:
<img width="310" height="181" alt="image" src="https://github.com/user-attachments/assets/4055fb05-5ab5-438a-9781-73eabb89979d" />

-- Write a SQL query to find the number of unique customers who purchased items from each category.:
<img width="437" height="131" alt="image" src="https://github.com/user-attachments/assets/c3e48296-7321-435d-948f-a5ba489faf0e" />

-- Write a SQL query to create each shift and number of orders (Example Morning <12, Afternoon Between 12 & 17, Evening >17):
<img width="675" height="416" alt="image" src="https://github.com/user-attachments/assets/b64c9577-89ea-46d6-96c6-c188d88ce751" />
