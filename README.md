
# Hypersel Apple Crawler

**Hypersel** is an advanced Python web scraper designed for Apple-related content. It uses Playwright for automated browsing, making it ideal for dynamic pages requiring clicks, scrolling, and pagination. The script can handle recursion, automatically finding and processing links within pages for deep data collection.

## Key Features

- **Dynamic Interactions**: Handles complex actions like scrolling and clicking through pages.
- **Error Recovery**: Automatically restarts if it encounters errors.
- **Configurable Scraping**: Set custom rules to extract exactly the data you need.
- **Data Cleaning**: Ensures consistent, clean data by removing special characters.

## Requirements

- Python 3.7+

## Installation

1. Install Hypersel:
   ```bash
   pip install hypersel
   ```

2. Run the script:
   ```bash
   python main.py
   ```

## Usage

1. **Configure** the fields you want to scrape as needed.
2. **Run the script** to begin scraping and collecting data.

Output data is saved in `data.json`.

For troubleshooting or more advanced configuration, refer to the code documentation.
