# IMDb Movie Reviews Scraper

Automated extraction of movie reviews from IMDb using Python and BeautifulSoup.

## Tech Stack
- Python
- Requests, BeautifulSoup4
- CSV / TXT module

## Project Overview
This project scrapes textual reviews of movies from IMDb, extracts the review content, and stores it in a text file for further use or analysis.

## Workflow
- Sent HTTP requests to IMDb movie review pages with proper headers
- Parsed HTML and extracted all textual reviews
- Structured and saved the extracted reviews into a text file

## Highlights
- Automated collection of movie reviews from IMDb
- Cleaned and formatted textual data for storage
- Created a reusable dataset for review exploration

## How to Run
Clone this repository:

```bash
git clone https://github.com/Divya6859/imdb-reviews-scraper.git
cd imdb-reviews-scraper
pip install -r requirements.txt
python scripts/MovieReviewsScrap.py
```


