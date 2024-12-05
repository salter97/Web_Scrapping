
# Web Scraping Esports Data For Data Analysis 

### Overview
This project is a web scraping tool designed to extract and analyze player statistics from the Apex Legends ALGS Playoffs Overview page.
### Process Overview
- **Web Scraping**: Utilized Beautiful Soup to parse HTML and extract data from a specific table on the webpage.
- **Data Extraction**: Retrieved table headers (columns) and player statistics (rows) from the table with ID `playersStatsTable`.
- **Data Cleaning**: Processed raw HTML data to remove unnecessary characters and formatted it for analysis.
- **Data Storage**: Structured the extracted data into a CSV file for easy access and further use.
### Link
- https://apexlegendsstatus.com/algs/Y4-Split2/ALGS-Playoffs/Global/Overview#tab-weaponsStats
### Output
The script outputs a CSV file (`algs.csv`) containing detailed player statistics, including columns like Player Name, Kills, Points, etc.
