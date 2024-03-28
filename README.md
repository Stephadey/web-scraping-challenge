# Module 11 Challenge: Mars Exploration Data Analysis

This project involves scraping and analysing data related to Mars, specifically from news articles and weather data tables. The goal is to extract insights from the Mars News website and analyse Mars weather data, providing a foundation for further exploration and study.

## Project Structure

The project is divided into two main parts:

-   **Part 1**: Scraping titles and preview text from Mars news articles.
-   **Part 2**: Scraping and analysing Mars weather data from a table.

### Deliverables

1.  `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news articles.
2.  `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analysing Mars weather data.
3.  `scraped_data.json`: Exported JSON file containing the scraped news titles and previews.
4.  `export_data.csv`: Exported CSV file containing the analysed Mars weather data.

## Part 1: Mars News Scraping

In this part, automated browsing is used to visit the Mars News site and scrape titles and preview texts of news articles. The scraped data is then stored in Python dictionaries within a list and exported to a JSON file (`scraped_data.json`).

### Steps to Run

1.  Open `part_1_mars_news.ipynb` in Jupyter Notebook or JupyterLab.
2.  Run all cells to perform the scraping.
3.  The resulting list of news articles will be printed and saved to `scraped_data.json`.

## Part 2: Mars Weather Data Analysis

This part involves scraping Mars weather data from a provided URL and analysing it using pandas. The analysis covers various aspects of the Martian weather, including temperature and atmospheric pressure, and exports the results to a CSV file (`export_data.csv`).

### Steps to Run

1.  Open `part_2_mars_weather.ipynb` in Jupyter Notebook or JupyterLab.
2.  Run all cells to scrape the weather data, perform the analysis, and export the DataFrame to `export_data.csv`.
3.  Explore the analysis results, including the number of Martian months, the range of temperatures, and atmospheric pressure variations.

## Requirements

-   Python 3.6+
-   Libraries: pandas, matplotlib, BeautifulSoup4, selenium (for web scraping)

## Setup

Ensure you have Jupyter Notebook or JupyterLab installed, along with the necessary Python libraries. For web scraping, a webdriver compatible with your browser is required (e.g., chromedriver for Google Chrome).

## Conclusion

This project provides an introductory exploration into web scraping and data analysis with Python, focusing on Mars-related data. 

## References

- [BeautifulSoup Documentation](https://pypi.org/project/beautifulsoup4/)
- [Matplotlib Documentation](https://matplotlib.org/stable/users/index.html)
- [The Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from [NASA's Mars News](https://mars.nasa.gov/) website in November 2022. 
