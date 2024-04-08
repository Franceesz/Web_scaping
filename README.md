# Web_scaping
This challenge demonstrates the usage of BeautifulSoup and Splinter with Selenium to collect data from websites without an API.

## Part 1, Mars News

In the [notebook for Part 1](part_1_mars_news.ipynb), I scraped the site, extracted the article title and preview text, then saved the extracted data to [mars_news.json](mars_news.json).

## Part 2, Mars Weather

In the [notebook for Part 2](part_2_mars_weather.ipynb), I scraped the site and extracted the table data to a pandas DataFrame. This data was saved to [mars_weather.csv](mars_weather.csv). I then analyzed the data to answer some questions:

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