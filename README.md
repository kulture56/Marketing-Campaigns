# Main-Campaign-Project
**Overview**
This project provides a comprehensive business analysis framework using SQLite. The repository contains scripts and data that focus on analyzing business campaigns through SQL commands for filtering, sorting, and aggregating business data.

**Key Features**
1) SQLite Database Management: Perform data analysis on campaign-related datasets using SQLite.
2) SQL Commands: A collection of scripts for filtering, sorting, and aggregating data.
3) Campaign Data: Access to real business datasets for in-depth analysis.
4) Documentation: Includes .docx files and SQL project configurations that guide users through the analysis process.
   
**Files and Directories**
1) SQL Scripts: Includes scripts for performing JOINs, filtering, and sorting data.
2) Project Analysis Files: Documentation and project files in .docx format detailing the campaign analysis.
3) Datasets: Business campaign datasets in SQLite format for analysis.



   **Key Inquiries and Solutions**
   
   
1) Which campaigns have generated the most revenue?
   
   a) Inquiry: To understand return on investment (ROI), we need to determine which campaigns generated the most revenue, while ensuring 
  that all campaigns, including those with no sales, are represented (with NULL values replaced by 0).

   b) Solution: The analysis revealed that we could track revenue by joining campaigns with interactions and sales data, sorting the 
  results by total revenue. This helps in identifying the most profitable campaigns.

2) Which campaign achieved the lowest acquisition cost per item sold?
   
   a) Inquiry: Determining marketing efficiency requires knowing which campaign managed to sell items at the lowest cost per item sold, 
   based on the campaign budget and total sales.

   b) Solution: By calculating the budget per item sold across all campaigns, we discovered the campaigns that had the most efficient 
   spending, offering insight into cost-effective marketing strategies.

3) Which interaction type led to the most sales?
   
   a) Inquiry: To optimize marketing channels, we must find out which interaction type (such as email, call, etc.) was most effective in 
   converting interactions into sales.

   b) Solution: Analyzing the interactions and their subsequent sales highlighted the most effective marketing channels, guiding future 
   marketing efforts.

4) What is the average amount spent and quantity purchased for each campaign?
   
   a) Inquiry: Understanding customer buying behavior involves evaluating the average amount spent and the average quantity purchased for 
   each campaign.

   b) Solution: We identified trends in customer spending and purchasing behavior for each campaign, with one campaign standing out for 
    having an average quantity purchased of 1.42 units.

5) Who are the top three customers who made the most purchases, and how much did they spend?
   
   a) Inquiry: Identifying the top three customers by purchase count and total spend provides insights into the most valuable customers 
   across campaigns.

   b) Solution: The analysis identified the three customers who contributed the most in terms of both frequency and total amount spent, 
   helping to target high-value customers more effectively.
