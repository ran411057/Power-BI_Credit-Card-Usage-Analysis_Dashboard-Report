**Project Overview**

Two dashboards have been developed to track the weekly data of credit card users, with new data being added and refreshed every week.

**Project Objective**

The goal is to create a detailed weekly credit card dashboard that offers real-time insights into key performance indicators and trends. This enables stakeholders to efficiently monitor and analyze credit card operations.

**Data Extraction**

I imported data from an SQL database by first preparing the CSV file. Then, I created tables in the SQL database and imported the CSV file into it. Lastly, I connected the data to Power BI for analysis.

**Data Processing & DAX Queries**

I reviewed the data for null values, duplicates, and other inconsistencies, especially for fields like gender and age. Using DAX queries, I created age and income group buckets and calculated the current and previous week's revenue.

**Dashboard and Insights**

There are two dashboards: Credit Card Transaction and Credit Card Customer.

**Credit Card Transaction Dashboard:** Filters are applied to analyze weekly data, including the number of male vs female users, income range (Low, Medium, High), card category (Blue, Silver, Gold, Platinum), and quarterly data. These filters are visualized using a tree map chart. Additionally, key performance indicators (KPIs) are highlighted using cards to show total revenue, generated interest, total transactions, the number of customer transactions, and total annual fees. Column charts are used to compare revenue across different metrics.

**Credit Card Customer Dashboard:** This dashboard is segmented by male and female users. A key chart compares weekly revenue by gender. Several filters are applied, and cards display total customer income and satisfaction scores.

**Export & Share**

The report was exported as a PDF, and the insights were recorded in a PowerPoint presentation, which was then shared with stakeholders.
