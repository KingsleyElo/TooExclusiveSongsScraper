# TooExclusive Songs Scraper
The code in the notebook is designed to scrape song details from the TooExclusive website, a popular platform for Nigerian music. The script extracts essential information including the song image link, name, description, and download link. The scraped data is then organized and saved into an Excel file for easy analysis and reference. The song name column can be further broken down into artist name and song title in Excel using the Text to columns under the Data tab.

**Note:** The website structure may change, impacting the scraper's functionality. Adjust the code accordingly.

## Table of Contents

- [Usage](#usage)
  - [Clone the Repository](#clone-the-repository)
  - [Install Dependencies](#install-dependencies)
  - [Run the Notebook](#run-the-notebook)
- [Contribution](#contribution)
- [Dangers of web scraping](#dangers-of-web-scraping)

## Usage

### Clone the Repository

"""bash
git clone https://github.com/KingsleyElo/TooExclusiveScraper.git
"""

### Install Dependencies
pip install -r requirements.txt<br>
Create a requirements.txt file in the root of your project with the following content:<br>
beautifulsoup4==4.11.2<br>
pandas==1.5.3<br>
requests==2.31.0<br>
**Note: I did not need to use pip to install any libraries, because I used Google Colab to run my code**

### Run the Notebook
Google Colab Too_exclusive_web_scraping_updated.ipynb

## Contribution
Contributions are welcome! Report issues or submit pull requests.

## Dangers of web scraping
**Note**: The information provided is intended for learning purposes only, and users should be aware of the potential legal and ethical risks associated with web scraping. It is recommended to review and comply with the terms of service of the target website and to exercise caution to avoid any adverse consequences such as IP blocking or legal actions.

