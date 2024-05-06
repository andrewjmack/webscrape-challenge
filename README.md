# webscrape-challenge
### Andrew Mack | DU Data Analytics | May 2024 

## Summary
This respository contains the files to meet the requirements of the webscraping module 11 homework challenge.

The challenge consists of two parts:
- Webscraping of Mars news article content
- Webscraping and analysis of Mars temperature table data

In addition to the Jupyter Notebooks used for webscraping and analysis, an Output folder contains a CSV file with the cleaned temperature data and .PNG charts to support the analysis.

## Repo Contents
- README
- part_1_mars_news.ipynb
- part_2_mars_news.ipynb
- Output
    - mars_data.csv
    - avg_pressure.png
    - avg_temp.png
    - avg_temp_cold_to_hot.png
    - martian_year.png

## Resources
- Initial Jupyter Notebooks with instructions provided
- URL for Mars news content for webscraping:
    - https://static.bc-edx.com/data/web/mars_news/index.html
- URL for Mars temperature data for webscraping:
    - https://static.bc-edx.com/data/web/mars_facts/temperature.html
- Class instruction and module activities
- Tutor assistance with embedded for loop to extract temperature table data
- Reference for writing dataframe to CSV:
    - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_csv.html

- Resetting the index creates a column of the previous index, used when plotting the count of terrestrial days:
    - https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.reset_index.html
