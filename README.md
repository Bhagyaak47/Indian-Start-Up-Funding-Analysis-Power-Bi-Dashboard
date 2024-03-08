# Indian-Start-Up-Funding-Analysis-Power-Bi-Dashboard

Indian startups have been making waves in recent years, attracting significant attention and
funding from investors both domestically & globally.

**Aim:**
The aim of this project is to analyze funding received by start-ups in India of year (2004, 2008,
and 2010 to 2019) and investigate the ecosystem.

**Data Collection:**

Indian start-up funding dataset of (2004, 2008, 2010 to 2019) year.

The Column names & Description are as follows:

1. Company/Brand: Name of the Company/Brand/Startup
2. Founded: Year start-up was founded.
3. Sector: Sector of service
4. What it does: Description about Company.
5. Founders: Founders of the Company.
6. Amount ($): Raised fund.
7. Stage: Round of funding reached.
   
**Data Cleaning:**

Cleaning of the data was done with Jupyter Notebook.
1. Founded Column: There were empty cells (Missing values) those were replaced with the
mode of the founded column that is most occurring year.
2. Headquarter:
-There were empty cells (Missing values) those were replaced with the mode of the founded
column that is most occurring Headquarter.
- Headquarter Column divided into 2 Columns (City & Country)
3. Sector:
- There were empty cells (Missing values) those were replaced with the mode of the founded
column that is most occurring Sector.
-There were some cases issues means same names but diff types.so I changed them into one &
replaced them.
4. Amount:
- The amount column was an integer but had strings of “undisclosed” was replaced with blanks
Then “$” and “,” too removed before getting the total values.
5. Stage:
-Had similar name & missing values issues. Similar naming replaced with uniform name &
Missing values replaced with the mode value of the column.

**Conclusion:**
In conclusion,
-The best course of action to take venturing into the Indian start-up ecosystem is venture into an
Edtech with its Headquarters in Bangalore.
-Bangalore as shown in the analysis plays a significant role in making startup successful, it has
the highest top 5 funded companies.
-Edtech has the highest funded company & also the most popular startup.
