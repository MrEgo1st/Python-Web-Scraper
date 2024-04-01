# Grab Food Restaurant Scraper

This project is a Python script for scraping restaurant information from the Grab Food website for a specific location in Singapore. It gathers details such as the restaurant name, cuisine, and image link, and then stores this data in both NDJSON and GZ formats.

## Prerequisites

Before running this script, make sure you have the following installed:

- Python 3.6 or higher
- Selenium WebDriver
- ChromeDriver
- BeautifulSoup4
- Requests
- Pandas

## Installation

Clone this repository to your local machine:

```sh
git clone https://github.com/MrEgo1st/Python-Web-Scraper
```

Navigate into the project directory:

```sh
cd grab-food-scraper
```

Install the required Python dependencies:

```sh
pip install -r requirements.txt
```

## Usage

To run the scraper, execute the following command in the terminal:

```sh
python scraper.py
```

This script will automatically open a Chrome window, navigate to the Grab Food URL, input a predefined location for delivery, scrape the restaurant data, and save it into restaurants_readable.ndjson and restaurants_readable.ndjson.gz files.

## Output

### The script outputs two files:

- restaurants_readable.ndjson - Contains the scraped data in NDJSON format, which is human-readable.
- restaurants_readable.ndjson.gz - A GZipped version of the NDJSON file for efficient storage.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.
