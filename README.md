# campaign-funds-2024

Webpage that tracks the campaign finances of candidates running for president in the U.S. elections in 2024. This data is auto-scraped from the Federal Elections Commission API https://www.fec.gov/data/

## Here's how I did it:
1. I started by applying for an API key to access the Federal Elections Commission data, OpenFEC.
2. From there, I narrowed down my search to presidential campaign finance data, and got the campaign finances of 12 candidates for president in the 2024 elections.
3. For this project, I focused on two things: cash on hand, and itemized individual donations.
* Cash on hand refers to the total funds available to the political committee at the conclusion of that particular reporting period. While, itemized individual donations refers to the total dollars raised from individual donations that have crossed the $200 aggregate threshold.
4. After preparing the data, I exported it to a .csv file and used github actions to update the file every 24 hours.
* Note that campaign finance data are not updated daily and is based on the reporting or filing period.
5. Now that the auto-scraper is running, I loaded it up to Datawrapper and put all the information into a graph.
6. The final step was putting it all in a website which I created using github pages.

  


