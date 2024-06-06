# Yellow Pages Web Scraper

## Description

This Python script scrapes Yellow Pages listings based on a search category and location, and saves the results to a CSV file. It also converts the CSV file to an Excel file.

## Requirements

- Python 3.x
- `requests` library
- `lxml` library
- `unicodecsv` library
- `pandas` library

## Usage

1. Clone the repository or download the `web-scraper.py` script.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the following command:

   ```bash
   python web-scraper.py {Search Category} {Location of Search}
   ```

   Replace `{Search Category}` with your desired search category and `{Location of Search}` with the location where you want to search.

   Example:

   ```bash
   python web-scraper.py restaurants New York
   ```

## Output

- The scraped data will be saved to a CSV file named `{Search Category}-{Location}-yellowpages-scraped-data.csv`.
- An Excel file named `{Search Category}-{Location}-yellowpages-scraped-data.xlsx` will be created from the CSV file.


- This script uses the Yellow Pages website for scraping. Make sure to comply with their terms of service.
- If you encounter any issues, ensure you have installed the required libraries and have a stable internet connection.

---

Feel free to customize the README further to include any additional information or instructions specific to your use case.
