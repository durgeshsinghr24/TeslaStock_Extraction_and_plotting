# TeslaStock_Extraction_and_plotting
This Jupyter Notebook showcases how to extract Tesla stock data from the website Macrotrends using web scraping techniques with BeautifulSoup, and perform data analysis and visualization using Pandas, Plotly, and yfinance libraries in Python.

Prerequisites
To run this notebook, you need to have the following Python libraries installed:

BeautifulSoup: For web scraping and parsing HTML data.
Pandas: For data manipulation and analysis.
Plotly: For interactive and visually appealing data visualization.
Requests: For making HTTP requests to retrieve web page content.

#Notebook Overview

Data Extraction: The web page URL is provided, and the BeautifulSoup and Requests libraries are used to scrape the HTML content of the page. Relevant data such as date, stock price, and revenue are extracted and stored in a Pandas DataFrame.

Data Cleaning and Preparation: The extracted data is cleaned and prepared for analysis. This includes converting data types, handling missing values, and organizing the DataFrame.

Data Analysis and Visualization: Using the cleaned data, various insights are derived and visualized using Plotly. The notebook demonstrates how to create interactive line plots to visualize the stock price and revenue trends over time.

Conclusion: A summary of the findings and observations from the data analysis process.

Note: This notebook assumes basic knowledge of Python programming, data manipulation with Pandas, and data visualization with Plotly. It serves as a practical example of utilizing web scraping techniques and data analysis libraries to extract and analyze Tesla stock data.
