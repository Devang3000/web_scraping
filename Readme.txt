Imports: The script imports necessary libraries: requests for HTTP requests, BeautifulSoup for HTML parsing, and csv for CSV file handling.

1.)Scraping Function (scrape_yellowpages):
Scrapes restaurant data from Yellow Pages UAE.
Iterates through each page, extracting details like name, location, phone numbers, etc.
Stops when no more pages are found.
Returns the scraped data as a list of dictionaries.

2.)CSV Saving Function (save_to_csv):
Saves scraped data into a CSV file.
Extracts column names from the data.
Writes data to the CSV file.

3.)Main Function (main):
Sets the base URL for restaurant listings.
Calls the scraping function and saves the data to a CSV file.

4.)Execution:
Runs the main function if the script is executed directly.
