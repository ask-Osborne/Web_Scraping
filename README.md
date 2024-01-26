# Web Scraping Showcase with Python

This Python script demonstrates my proficiency in web scraping using the BeautifulSoup library. The target for this project is the Wikipedia page for the 2022–23 Premier League. The goal is to extract relevant information from a specific table on the page.

# Script Explanation
The script uses `requests` to fetch the HTML content of the Wikipedia page.
`BeautifulSoup` is then employed to parse the HTML and navigate the document's structure.
The specific table of interest is located using the `find_all('table')[2]` method.
The table's rows and columns are extracted and processed to create a Pandas DataFrame.
The resulting DataFrame is saved as a CSV file.

# Showcase Highlights
- **Web Scraping Technique:** Utilizing `BeautifulSoup` for parsing HTML and navigating the document structure.
- **Data Extraction:** Focusing on a specific table on the Wikipedia page to showcase targeted information extraction.
- **Script Organization:** A well-organized Python script with clear comments and explanations.

# Dependencies
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [requests](https://docs.python-requests.org/en/master/)
- [wikitextparser](https://github.com/earwig/wikitextparser)
- [pandas](https://pandas.pydata.org/)
  
