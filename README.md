# Philips-Auction-Data-Scraping
Scraping data from Philips on the most recent auctions.

The following is the code used to scrape auction data from the given sites (Section 1. Phillips Data Scraping), as well as the code (Section 2. Cleaning Artist Years Alive Table) used to clean table 1 (Data Strategy Art Market Case Study Data Tables 2 and 3/Data Table 2-Table 1.csv) which provides the lifespan of certain artists. <br>
- "https://www.phillips.com/auctions/auction/UK010122"
- "https://www.phillips.com/auctions/auction/UK030122"
- "https://www.phillips.com/auctions/auction/HK010321"
- "https://www.phillips.com/auctions/auction/NY010721"
- "https://www.phillips.com/auctions/auction/UK010921"
<br>
The code extracts the following fields and performs preliminary data cleaning and organizes the data into a DataFrame that is exported to a .csv file for it to be imported into Airtable.
"Artist Name",
"Title of Work",
"Date of Sale",
"Local Currency",
"Low Estimate (USD)",
"High Estimate (USD)",
"Transaction Price (USD)",
"Source" (the website where the instance
