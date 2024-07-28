# School Info Scraper

## Overview
This project is a web scraping tool built with Python, Selenium, and BeautifulSoup. It extracts information about schools, such as their names and URLs, from a specified website. The scraped data is then stored in a pandas DataFrame and can be saved to a CSV file for further analysis.

## Features
- Clicks through different continents and countries to gather school information.
- Extracts school names and URLs.
- Stores the extracted data in a pandas DataFrame.
- Option to save the data to a CSV file.

## Requirements
- Python 3.x
- Selenium
- BeautifulSoup4
- chromedriver-autoinstaller
- pandas

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/school-info-scraper.git
    ```
2. Navigate to the project directory:
    ```sh
    cd school-info-scraper
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have Google Chrome installed.
2. Run the script:
    ```sh
    python scraper.py
    ```
3. The script will navigate through the website, click on different regions and countries, and extract the required school information.

## Output
- The scraped data is stored in a pandas DataFrame.
- Optionally, the data can be saved to a CSV file.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


## Acknowledgements
- This project uses the [Selenium](https://selenium.dev/) library for web automation.
- BeautifulSoup is used for parsing HTML content.



