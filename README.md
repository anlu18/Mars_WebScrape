

---

## Mars Data Exploration Project

### Overview
This project is a comprehensive two-part exploration of Mars-related data, focusing on web scraping and data analysis. In the first part, we gather the latest Mars news headlines and previews, while the second part centers on scraping and analyzing Mars weather data, specifically temperature and atmospheric pressure.

### Part 1: Mars News Scraping

#### Description
In the first part of this project, we utilize web scraping techniques to retrieve the most recent Mars news titles and preview texts from a designated website.

#### Process
- **Automated Website Access:** We employ automated web browsing to navigate to the Mars news website.
- **Data Scraping:** A Beautiful Soup object is used to extract the relevant text elements, such as news titles and previews, from the site.
- **Results Storage:** The scraped news titles and preview texts are stored in Python data structures for further use.

### Part 2: Mars Weather Data Scraping and Analysis

#### Description
The second part of the project involves scraping and analyzing Mars weather data, with a particular focus on temperature and atmospheric pressure readings.

#### Process
- **Automated Website Access:** Similar to Part 1, we use automated web browsing to access a website that provides Mars temperature data.
- **Table Data Scraping:** The HTML table containing weather data is extracted using Beautiful Soup.
- **Data Organization:** The scraped data is structured into a Pandas DataFrame for easier manipulation and analysis.
- **Data Preparation:** We carefully examine and convert data types as necessary to ensure accuracy.
- **Data Analysis:** Key questions are addressed using Pandas functions, and data visualizations are created to enhance understanding.
- **Data Storage:** The cleaned and analyzed data is saved to a CSV file for future reference.

### Usage
To replicate this project, follow these steps:

1. Ensure the necessary libraries are installed, including Splinter, BeautifulSoup, Pandas, and Matplotlib.
2. Open the provided Jupyter Notebooks (`part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`) and follow the instructions to run the code.

### Data Storage
The results of the data gathering and analysis are stored as follows:

- **Mars News Data:** The scraped news titles and previews are saved in JSON format, available in the `scraped_data.json` file.
- **Mars Weather Data:** The weather data, after thorough analysis, is stored in a CSV file named `mars_weather_data.csv`.

---

