# Books Web Scraper Project

### Description
This project focuses on scraping book data from the [Books to Scrape](http://books.toscrape.com/) website. The goal is to extract the title, price, and star rating of books from multiple pages and save the data in a CSV file for analysis.

### Web Scraping Process
The following steps were implemented using Python, BeautifulSoup, and Requests:

#### 1. **Extract Book Information**
   - Scraped multiple pages of book listings, extracting the title, price, and star rating for each book.
   - Each page contains multiple book entries, which are parsed and processed into structured data.

#### 2. **Price Conversion**
   - Converted the price from a string format to a float for easier manipulation in any subsequent analysis.

#### 3. **Save Data to CSV**
   - Stored the extracted data in a CSV file named `books.csv`, with columns for title, price, and star rating.

### Sample Output
The scraped data includes information like:

| Title               | Price | Star Rating |
|---------------------|-------|-------------|
| A Light in the Attic | 51.77 | Three       |
| Tipping the Velvet   | 53.74 | One         |
| Soumission           | 50.10 | Five        |

### Libraries Used
- **BeautifulSoup**: For parsing and scraping HTML content.
- **Requests**: For sending HTTP requests and retrieving webpage data.
- **Pandas**: For organizing and saving the data into a CSV file.

The scraped data can be used for further analysis or visualization in any data analytics projects.
