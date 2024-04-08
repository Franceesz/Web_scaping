# Web_scaping
This challenge demonstrates the usage of BeautifulSoup and Splinter with Selenium to collect data from websites without an API.
Automated browsing was enabled by **Splinter** and **WebDriver Manager**. **BeautifulSoup** objects were created to extract HTML code for both Jupyter Notebooks. 
`part_1_mars_news.ipynb` scrapes Mars news from web and stores the information in a list of Python dictionaries. 
`part_2_mars_weather.ipynb` scrapes Mars temperature/weather information from the web and stores the information into a Pandas DataFrame.
`mars_temperature_data.csv` is the output csv file for the Pandas DataFrame with Mars temperature/weather information from part 2. 

### Part 1: Scrape Titles and Preview Text from Mars News
- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). 
- The titles and preview text of the news articles were scraped and extracted, and stored in a list of dictionaries.

## Part 2, Mars Weather

In the [notebook for Part 2](part_2_mars_weather.ipynb), I scraped the site and extracted the table data to a pandas DataFrame. This data was saved to https://github.com/Franceesz/Web_scaping/blob/main/mars_df.csv. I then analyzed the data to answer some questions:

1. How many months on Mars?
    - 12 months
2. How many Martian days of data are there?
    - 1,867 days
3. What are the coldest and warmest months on Mars?
    - Coldest: Month 3
    - Warmest: Month 8
4. Which months have the hightest and lowest atmospheric pressure on Mars?
    - Hightest: Month 9
    - Lowest: Month 6
5. About how many Earth days exist in a Martian year?
    - About 675 Earth days.
