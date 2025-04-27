# Product Review and Sentiment Analyzer

## Overview

This project is a Product Review and Sentiment Analyzer that utilizes web scraping to gather product reviews from various sources. The sentiment of the reviews is analyzed, and the results are visually represented using a word cloud. Positive ratings are highlighted in green, while negative ratings are shown in red. The application is built using the Flask web framework.

## Features

- Web scraping to collect product reviews
- Sentiment analysis of reviews
- Visual representation of sentiments using word clouds
- User-friendly web interface

## Libraries Used

This project utilizes the following libraries:

- `nltk`: For natural language processing tasks
- `wordcloud`: To generate word clouds from the review data
- `flask`: To create the web application
- `bs4 (BeautifulSoup)`: For web scraping
- `urllib`: For handling URLs

## Usage
- Run the Flask application:
   python app.py
- Open your web browser and navigate to http://127.0.0.1:5000/.
- Enter the product URL you want to analyze and submit the form.
- View the sentiment analysis results and the generated word cloud.
