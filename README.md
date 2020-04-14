# Analyzing Startup Fundraising Deals from Crunchbase
In this project, I mainly did a couple of things: optimized dataset memory usage, and then analyzed the dataset using sqlite3. the dataset we'll be exploring is startup investments from [Crunchbase.com](https://crunchbase.com/), the dataset is current as of October 2013. 

Crunchbase is a website that crowdsources information on the fundraising rounds of many startups. The Crunchbase user community submits, edits, and maintains most of the information in Crunchbase. Crunchbase information includes investments and funding information, founding members and individuals in leadership positions, mergers and acquisitions, news, and industry trends.

Using the data, I optimized the dataset by dropping the columns that are unneccesary and redudant for data analysis and identify the types for each column to find the optimal types for each columns, then I export the dataset into a table in a SQLite database so i can query the entire dataset.

You can see the exploratory data analysis in the `Exploration.ipynb` notebook above. You can see the Crunchbase sample data (in csv format) and SQLite database (in .db format) in the `data` folder.
