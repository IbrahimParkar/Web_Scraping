# Web Scraping Project

This project involves scraping data from the [Wikipedia page listing the largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue) and storing it in a Pandas DataFrame. The output data is saved in `Companies.csv` for further analysis.

## Introduction
The goal of this project is to scrape the Wikipedia page that lists the largest companies in the United States by revenue, storing the extracted data in a CSV file for easy analysis and manipulation. The data includes information such as company name, revenue, industry, and headquarters location.

## Technologies Used
- **Requests**: For making HTTP requests to the Wikipedia page.
- **BeautifulSoup**: For parsing HTML and extracting the relevant data.
- **Pandas**: For storing, manipulating, and saving the scraped data in CSV format.

## Usage

1. Open the Jupyter notebook file `Web Scraping.ipynb` in your preferred environment (e.g., JupyterLab or Google Colab).
2. Run the notebook to scrape the data from the Wikipedia page.
3. The data will be automatically stored in `Companies.csv` after scraping.

### Example Output
The extracted data is saved in `Companies.csv`, with columns such as:

| Rank | Name          | Industry         | Revenue (USD Billions) | Employees | Headquarters     |
|------|---------------|------------------|------------------------|-----------|------------------|
| 1    | Walmart       | Retail            | 572.8                  | 2,300,000 | Bentonville, AR   |
| 2    | Amazon        | Technology        | 469.8                  | 1,500,000 | Seattle, WA       |
| 3    | Apple         | Technology        | 365.8                  | 154,000   | Cupertino, CA     |

## Files

- `Web Scraping.ipynb`: The Jupyter notebook containing the web scraping code.
- `Companies.csv`: The output file containing the scraped data from the Wikipedia page.

## Contributing
If you'd like to contribute to this project, feel free to submit a pull request. For major changes, please open an issue to discuss what you would like to change.
