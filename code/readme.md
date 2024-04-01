# Script Overview

The script operates in two phases:
- **Extraction:** Opens Yelp, performs a search for "Indian" restaurants, navigates through a predefined number of result pages, and saves each page's HTML.
- **Transformation and Loading:** Parses the saved HTML files to extract restaurant names and locations, cleans the data, and saves the results in a CSV file for easy use.

## Script Customization
- **Search Term:** Modify the `send_keys` method's argument in the `extraction` function to change the search criteria.
- **Number of Pages:** Adjust the `number_of_page` variable to increase or decrease the number of pages you wish to scrape.
