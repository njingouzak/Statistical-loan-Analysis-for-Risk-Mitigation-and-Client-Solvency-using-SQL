# Statistical loan Analysis for Risk Mitigation and Client Solvency using SQL

This project seeks to uncover meaningful trends and patterns that can inform more prudent and sustainable lending decisions. By translating data into actionable insights, it supports financial professionals in making well-informed decisions, strengthening risk assessment processes, and promoting responsible lending practices. In the ever-evolving financial services landscape, ensuring responsible lending while minimizing risk remains an ongoing priority. Although financial institutions face complex challenges, these very complexities present a powerful opportunity: leveraging statistical analysis to drive smarter, evidence-based decision-making.
## Dataset
This dataset encompasses important informations related to loan granted for different projects. It is structured with the following columns:  
  
**- Listing Number:** Identifier assigned to each loan  
**- Term:** Duration of the loan  
**- Loan status:** Current status of loan  
**- Borrower Rate:** Interest rate at which the borrower is charged for the loan  
**- Estimated Effective Yield:** indicates an estimate of the overall return on investment for the lender  
**- Estimated Loss:** Predicts the potential loss associated with the loan  
**- Estimated Return:** Forecasts the expected return for the lender  
**- Prosper Rating (Alpha):** Graded classification of the borrower's creditworthiness  
**- Occupation:** Profession of borrower  
**- Employment Status:** Indicates whether the borrower is employed, unemployed, or others  
**- Is Borrower Homeowner:** Specifies whether the borrower owns a home  
**- Loan Original Amount:** Represents the initial amount of the loan requested by the borrower  
**- Monthly Loan Payment:** Represents the regular monthly payment the borrower is required to make  
**- Investors:** Indicates the number of investors participating in the loan
## Tools
Python  
Pandas  
SQL connector  
MySQL Workbench  
  
## Content
### Module 1
### Task 1: Analyzing Load data
By exploring this dataset, we aim to ensure that each loan decision is grounded in rigorous statistical evaluation, thereby reducing risk and supporting long-term client success. Leveraging Python and library pandas, we transform raw data into actionable insights that foster more informed lending decisions and contribute to a stronger financial future for both clients and institution.  
  
### Task 2: Identifying Duplicate Data
We address the task of identifying duplicate entries within our loan records to ensure the accuracy and reliability of our financial data. By counting redundancies, we pursue the goal of producing a clean and well-structured dataset, minimizing the risk of errors and strengthening our capacity to deliver transparent, trustworthy financial services to our clients.  
  
### Task 3: Removing Duplicate Data for precision Lending
We embark on this task to enhance the efficiency and accuracy of our lending operations. By eliminating duplicates, we create a streamlined and accurate database that reinforces our commitment to responsible lending. Each redundant record removed helps ensure that our clients’ financial journeys are clear, consistent, and free from confusion or ambiguity.  
  
### Task 4: Addressing Null Values
In this task, We focus on identifying and resolving null values within the loan dataset to ensure the completeness and reliability of our financial records. By understanding and addressing missing data, we create a comprehensive and trustworthy dataset that supports more accurate analysis and informed lending decisions.  
  
### Task 5: Ensuring Data Completeness
We undertake this effort to ensure that our financial records are robust and complete. By eliminating missing values, we deliver a reliable and comprehensive loan dataset that enables well-informed lending decisions. Each null value addressed strengthens the accuracy and dependability of our data foundation, ultimately supporting the financial stability and success of our clients.  
  
### Module 2
### Task 1: Renaming Columns fo Clarity¶
We undertake the task of renaming columns within the loan dataset to improve data readability and interpretability. By giving clear, intuitive, and descriptive column names, we facilitate more efficient analysis and ensure a better understanding of the data. Each renamed column brings us closer to a dataset that communicates clearly and concisely, supporting more informed analysis and a more efficient lending process for the benefit of our clients.  
  
### Task 2: Categorizing for Efficiency
In this task, we are in the process of categorizing selected columns within the loan dataset to optimize data storage and improve processing efficiency. By converting appropriate variables to categorical data types, we reduce memory usage and accelerate data analysis. Each categorized column moves us closer to a more agile and efficient dataset, enabling faster analysis and more data-driven lending decisions for the benefit of our clients.  
  
### Task 3: Archiving the insights
In this task, we are carrying out a action to save our loan dataset as a CSV file, ensuring that our valuable insights and lending history are securely preserved for easy retrieval and future analysis.  
    
### Task 4: Data Download, Import, and Database Connection
In this part of our project, we begin by using the necessary SQL libraries previously load to establish a connection to the MySQL database. To load the data, we will use MySQL Workbench. First, log in to our local MySQL instance. Once connected, we created a new schema to house our table named loans_data. After the schema is set up, we use the Table Data Import Wizard in MySQL Workbench to load our CSV file. During the import process, Workbench prompt us to specify the data type for each column. In the process of creating the connection with our database, we should specified the hostname, username, password and database name from MySQL Workbench.  
  
### Module 3
### Task 1: Glimpse into the World of Loans
In our effort to understand the scope of our loan dataset, we perform a fundamental yet crucial task by counting the records. This step helps us gauge the scale of our lending operations and assess the volume of data available. By determining the number of records, we gain a clear sense of the size and analytical potential of the loan dataset. Each count brings us closer to a deeper understanding of our data, laying the foundation for more informed decisions and strategic planning in lending.  
  
### Task 2: Profiling Loan Data
In this task, we undertake this analysis to deepen our understanding of interest rates and loan amounts. By selecting, counting, and aggregating key data points within a specified interest rate range, we uncover meaningful statistics. Each metric we compute illuminates patterns in the lending landscape, providing a clearer, more comprehensive view of how interest rates and loan amounts vary and interact.  
  
### Task 3: Navigating Loan Metrics
In this task, We undertake the process of uncovering valuable insights into loan amounts and employment status. By aggregating the total loan amount for each employment group, we gain a comprehensive understanding of our lending practices.  
  
### Task 4: Charting the Loan Landscape
We undertake a task to group and count loans by their duration and status. This structured approach reveals patterns and trends across our loan portfolio, offering clarity on how loans are distributed across various durations and repayment statuses. These insights empower us to make more informed decisions, refine our strategies, and tailor our lending products to better meet our clients’ needs.    
    
### Task 5: Employability and Interest Rates
Our task focuses on exploring the relationship between employment status and interest rates in our loan dataset. By analyzing how employment categories correlate with borrowing costs, we aim to understand the distribution of loans across different employment types. Using SQL’s grouping and aggregation capabilities, we calculate average interest rates for each employment status, revealing key patterns. These insights enable us to refine our lending strategies, offer more competitive and equitable rates, and better serve borrowers based on their employment circumstances—supporting a more inclusive and responsive lending approach.  
  
### Task 6: Homeownership and Interest Rates
We undertake this task to understand how homeownership influences borrowing costs and to evaluate how loans are distributed between homeowners and non-homeowners. By using SQL to group and aggregate the data, we uncover average interest rates for each group, revealing meaningful differences tied to housing status. These insights allow us to refine our lending strategies—offering more competitive, tailored rates based on homeownership—and support a more inclusive, client-centered approach to financial services.  
  
### Task 7: Unpacking Prosper Ratings
In this task, we aim to explore how creditworthiness reflected in Prosper rating categories affects borrowing costs and shapes loan distribution. By leveraging SQL’s grouping and aggregation capabilities, we derive average interest rates for each rating tier, revealing how risk assessment translates into pricing. These insights help us better align lending terms with borrower profiles, supporting fairer, more strategic, and data-informed credit decisions.  
    
### Task 8: Loan Amount and Monthly Payment
We perform this task to understand how loan size influences borrowers' monthly financial obligations. By leveraging SQL’s grouping and aggregation functions, we analyze average monthly payments across different loan amount categories, revealing how borrowing levels translate into repayment commitments. This insight helps inform more transparent and borrower-friendly lending practices.  
  
### Task 9: Examining Interest Rates and Lending Dynamics
In this task, We aim to explore how investor involvement affects borrowing costs and to better understand how loans are distributed across varying levels of investor participation. Using SQL’s grouping and aggregation capabilities, we uncover average interest rates tied to different investor scenarios—revealing how funding dynamics influence loan pricing and informing more strategic, data-driven lending decisions.  
  
### Task 10: Loan Durations and Return Rates
We embark on this task to understand how loan duration influences investor returns and to evaluate how loans are distributed across different timeframes. By applying SQL’s grouping and aggregation functions, we uncover average return rates for loans of varying lengths, revealing how term length correlates with investment performance. These insights support more informed capital allocation and help align loan structures with investor expectations.  
  
### Task 11: Prosper Ratings and Return Rates
We undertake this task to understand how creditworthiness represented by Prosper rating categories affects investment returns for our stakeholders and to assess how loans are distributed across these risk tiers. By leveraging SQL’s grouping and aggregation capabilities, we derive average return rates for each rating category, revealing the relationship between borrower risk profiles and investor performance. These insights support more strategic investment decisions and help align portfolio allocations with risk-return objectives.  
  







