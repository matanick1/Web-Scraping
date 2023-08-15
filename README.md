# README

## Mars Data Analysis

This project focuses on scraping and analyzing various data related to Mars, including news and weather information. The data is sourced from different websites, processed, and stored for further analysis.

### Files Included:

1. `mars_weather.csv` - Contains weather data from Mars.
2. `part_1_mars_news.ipynb` - A Jupyter notebook that scrapes titles and preview text from a Mars news website.
3. `part_2_mars_weather.ipynb` - A Jupyter notebook that scrapes and analyzes Mars weather data.

## File Descriptions:

### 1. mars_weather.csv

This CSV file contains the following columns related to Martian weather:

- **id**: A unique identifier for each entry.
- **terrestrial_date**: The date on Earth.
- **Sol**: The Martian day number.
- **ls**: Possibly related to the position of Mars in its orbit.
- **month**: The Martian month.
- **min_temp**: Minimum temperature for the given date.
- **pressure**: Atmospheric pressure on Mars for the given date.

### 2. part_1_mars_news.ipynb

This Jupyter notebook is focused on:

- **Visiting a Mars news site**: Automated browsing and element inspection.
- **Scraping the website**: Using Beautiful Soup to extract news titles and preview text.
- **Storing the results**: Extracted data is stored in Python data structures.

### 3. part_2_mars_weather.ipynb

This Jupyter notebook involves:

- **Visiting the Mars Temperature Data Site**: Automated browsing and element inspection.
- **Scraping the table**: Extracting data from an HTML table using Beautiful Soup.
- **Storing and preparing data**: Assembling data into a Pandas DataFrame and converting data types.
- **Data analysis**: Answering various questions about Martian months, temperatures, and atmospheric pressures.
- **Saving the data**: Exporting the processed data to a CSV file.

## How to Use:

1. **For the Jupyter Notebooks**:
   - Open the respective notebooks in Jupyter Notebook or Jupyter Lab.
   - Ensure that all dependencies are installed.
   - Run the cells in sequence to conduct the respective scraping and analysis tasks.

2. **For the CSV Data**:
   - You can import the `mars_weather.csv` file into any data processing or analysis tool of your choice.

## Notes:

- Ensure you have the required Python packages installed, such as Beautiful Soup, Pandas, and others mentioned in the notebooks.
- Web scraping depends on the structure of the website. If the structure of the source websites changes, the scraping code may need adjustments.
