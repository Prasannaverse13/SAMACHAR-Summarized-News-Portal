## SAMACHAR: Summarized News Portal

The Summarized-News-Portal is an innovative web application designed to streamline how users access and consume news. Utilizing advanced Machine Learning (ML) and Natural Language Processing (NLP) techniques, this project delivers concise summaries of news articles from various sources.

The process begins with data collection, where the application gathers articles through RSS feeds using the Newspaper3k library. This ensures a wide range of topics and diverse viewpoints. Next, during data processing, NLP algorithms analyze the content, employing techniques like tokenization to break down text and summarization models to extract essential information, resulting in clear and concise summaries.



## Features

- **Trending News**: Displays the latest trending news from Google News.
- **Search by Topic**: Allows users to search for news articles based on custom topics.
- **Category News**: Browse news in predefined categories such as World, Business, Technology, Entertainment, Sports, Science, and Health.
- **Summarized Articles**: Provides concise summaries of news articles with the ability to read more.
- **Image Support**: Displays images associated with news articles.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

2. **Set up a virtual environment**:
```sh
    python -m venv venv 
```
3. **Activate the virtual environment**:
```sh
    venv\Scripts\activate
```
4.  **Install the required packages**:
```sh
    pip install -r requirements.txt
``` 
5. **Install Streamlit and additional dependencies**:
```sh
    pip install streamlit newspaper3k
``` 
6. **Install bs4 (BeautifulSoup4)**:
```sh
pip install beautifulsoup4
```
7. **If you encounter any issues with lxml, install it using**:
```sh
pip install lxml[html_clean]
```
8.**Run the Streamlit app**:
```sh
streamlit run App.py
```

## Project Structure
```
SAMACHAR/
│
├── App.py                       # Main application file
├── sample_news_scrap.py         # Sample news scraping script
├── requirements.txt             # Required Python packages
├── Meta/                        # Directory containing image assets
│   ├── newspaper.ico
│   ├── samachar11.png
│   ├── no_image.jpg
│   ├── default_image.png
│   └── screenshot.jpg           # Screenshot of the application
└── README.md                    # Project documentation
```

## Screenshots

![Screenshot (843)](https://github.com/user-attachments/assets/78d823f5-3da8-492e-bc88-e16106cfb98b)









