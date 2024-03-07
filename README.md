# campaign-funds-2024

This project provides a comprehensive overview of the campaign finances for candidates running for president in the U.S. elections in 2024. The data is automatically scraped from the Federal Elections Commission API (OpenFEC).

## How It Works

## Obtaining Data
- The process began with the acquisition of an API key to access the Federal Elections Commission data from OpenFEC.
- After obtaining the API key, the focus was narrowed down to gather presidential campaign finance data.
- The data obtained includes detailed financial information for 12 candidates participating in the 2024 presidential elections.

## Data Analysis
- The project primarily focuses on two key aspects: "cash on hand" and "itemized individual donations."
- "Cash on hand" refers to the total funds available to the political committee at the conclusion of each reporting period.
- "Itemized individual donations" encompass the total dollars raised from individual donations that have crossed the $200 aggregate threshold.

## Data Processing and Automation
- The collected data was processed and exported to a .csv file for further analysis.
- To ensure the data remains up-to-date, GitHub Actions were implemented to automatically update the file every 24 hours.
- It's important to note that campaign finance data isn't updated daily and depends on the reporting or filing period.

## Data Visualization
- The processed data was then visualized using Datawrapper, providing an intuitive graphical representation.
- Graphs and charts offer a clear insight into the financial aspects of each candidate's campaign.

## Website Deployment
- Finally, the compiled information was integrated into a website hosted on GitHub Pages.
- This website serves as a user-friendly platform to access and explore the campaign finance data conveniently.


