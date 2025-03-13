# British Airways WebScraper Project

This repository contains a web scraping and data analysis project that collects and analyzes customer reviews of British Airways from the AirlineQuality website. The analysis includes sentiment analysis, visualization of review distributions, and an overall recommendation rate. The results are presented in various forms, including a Word Cloud, bar charts, and pie charts, and are summarized in a PowerPoint presentation.

## Features

- **Web Scraping**: Scrapes customer reviews and ratings for British Airways from multiple pages of the AirlineQuality website.
- **Sentiment Analysis**: Analyzes the sentiment of each review text to determine customer feelings (positive, negative, or neutral).
- **Visualization**: Creates visualizations such as word clouds, histograms, bar charts, and pie charts for better insights.
- **Presentation**: Automatically generates a PowerPoint presentation summarizing the analysis and key insights.

## Requirements

- `requests`
- `pandas`
- `beautifulsoup4`
- `textblob`
- `wordcloud`
- `matplotlib`
- `seaborn`
- `python-pptx`

You can install the required dependencies using the following command:

```bash
pip install requests pandas beautifulsoup4 textblob wordcloud matplotlib seaborn python-pptx
```

## Project Structure

- `data/<project-name>.csv`: Contains the scraped review data, including the review text and ratings.
- `word_cloud.png`: The generated Word Cloud visualization of customer reviews.
- `average_ratings.png`: A bar chart showing the average ratings for different service categories.
- `sentiment_distribution.png`: A histogram showing the distribution of sentiment scores.
- `recommendation_rate.png`: A pie chart showing the percentage of customers who would recommend British Airways.
- `<project-name>.pptx`: The PowerPoint presentation summarizing the analysis and insights.

## How to Run

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/<project-name>.git
    cd <project-name>
    ```

2. Run the script to scrape data and perform analysis:

    ```bash
    python main.py
    ```

3. After running the script, the analysis results will be saved as images and a PowerPoint presentation (`<project-name>.pptx`).

## License

This project is licensed under the MIT License.

## Acknowledgements

- [AirlineQuality](https://www.airlinequality.com) for providing the review data.
- [TextBlob](https://textblob.readthedocs.io/en/dev/) for sentiment analysis.
- [WordCloud](https://github.com/amueller/word_cloud) for generating word clouds.
- [python-pptx](https://python-pptx.readthedocs.io/en/latest/) for creating PowerPoint presentations.
