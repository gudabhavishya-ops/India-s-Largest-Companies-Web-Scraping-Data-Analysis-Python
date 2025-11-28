India’s Largest Companies — Web Scraping & Data Analysis
Scraped from Wikipedia using Python (BeautifulSoup + Pandas)

# Overview
This project scrapes financial and company data from Wikipedia to analyze India’s largest companies based on revenue, profits, assets, and market value.
The scraped data is cleaned, transformed, and visualized to provide clear insights into the structure of India’s corporate landscape.
This project demonstrates strong skills in web scraping, data cleaning, visualization, and exploratory data analysis (EDA).

# Source
Data scraped from:
https://en.wikipedia.org/wiki/List_of_largest_companies_in_India – List of India's Largest Companies

# Data Extracted
The following columns were collected:


Rank (India)


Forbes 2000 Rank


Company Name


Headquarters


Revenue (Billion USD)


Profit (Billion USD)


Assets (Billion USD)


Market Value (Billion USD)


Industry


Total companies scraped: 70

# Tools & Libraries


BeautifulSoup → Web scraping


requests → Fetching HTML content


pandas → Data cleaning & transformation


matplotlib → Visualizations


seaborn → Statistical graphics



# Data Cleaning Steps
Performed directly inside the notebook:


Removed commas, symbols, and formatting errors


Converted Revenue, Profit, Assets, Value to float


Standardized column names


Ensured all numeric financial fields are type-correct



# Exploratory Data Analysis (Visuals + Insights)

Most companies have revenues below 20 billion USD, with only a few extremely large companies crossing the 50–100B USD mark.
The distribution is right-skewed, showing India has only a small number of super-giant firms.

Most companies earn 0–2 billion USD profit, while only a few achieve very high profits (5B–8B USD).
This indicates thin margins across many industries, with profitability concentrated in a few giants.

Banking and Financial sectors dominate—having the largest number of top companies.
Many industries have only 1–2 companies, showing uneven representation.

Higher revenue does not always mean higher profit.
Many high-revenue companies still report low profits, proving that efficiency matters more than size.
Only a few companies belong to the high-revenue, high-profit category.

Banking and Oil & Gas contribute the highest total revenue—far ahead of all other sectors.
Industries like Retail, Telecom, Consumer Goods, and Pharma contribute relatively smaller amounts.

High assets do not necessarily translate into high valuation.
A large cluster of companies holds huge assets but low market value—common in regulated or capital-heavy industries.
Only a few firms effectively convert assets into shareholder value.

# Overall Insights (Conclusion)
India’s corporate landscape is dominated by a small group of massive companies, especially in Banking, Oil & Gas, and Insurance sectors.
The financial sector contributes the highest revenue and assets, reflecting its central role in the economy.
Key patterns:


Revenue and profit are right-skewed—few giants, many mid-scale companies


High revenue does not guarantee high profitability


Asset-heavy firms often show lower valuations


Industry distribution is highly uneven


Mid-scale companies form the majority, but mega-corporations drive the economy


Overall, the analysis reveals a concentrated, finance-driven economy, with clear structural imbalances and growth opportunities.



# What You Demonstrate With This Project


Real web scraping from a live website


BeautifulSoup parsing skills


Financial data cleaning using pandas


Multiple EDA visualizations


Ability to derive insights from messy data


A solid end-to-end data analysis workflow


##  Author
**G.L.Bhavishya**

##  Contact
- Email: gudabhavishya@gmail.com 
- LinkedIn: www.linkedin.com/in/bhavishya-guda-803b46264  




