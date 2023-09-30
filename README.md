
# Web Scraping Project: Books to Scrape

## Project Description

This project aims to scrape data from the "Books to Scrape" website, specifically targeting books with a 2-star rating. At the end of the scraping process, we will have a list containing the titles of all books that have received a 2-star rating.

## Objectives

- Scrape the "Books to Scrape" website.
- Filter and retrieve titles of books with a 2-star rating.
- Store and present the results in a user-friendly format.

## Tools & Technologies

- **Language:** Python
- **Libraries:** 
  - `requests`: For making HTTP requests to the website.
  - `BeautifulSoup`: For parsing the HTML content and extracting the required data.

## Steps to Execute the Project

1. **Setup**:
   - Make sure you have Python installed.
   - Install the necessary libraries:
     ```
     pip install requests beautifulsoup4
     ```

2. **Execution**:
   - Run the main script (e.g., `scraper.py`) to start the scraping process.
   - Once the script has executed, check the output file or console for the list of book titles with a 2-star rating.

3. **Output**:
   - The titles of books with a 2-star rating will be displayed in the console or saved to an output file (as per your configuration).

## Note

Ensure you respect the website's `robots.txt` file and terms of service. Web scraping might be against the terms of service for some websites. It is important to scrape responsibly and ethically.
