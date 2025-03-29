# UEFA Champions League Standings Scraper

## Description
This project is a web scraper built using **Scrapy** to extract UEFA Champions League standings data from the ESPN website. The extracted data includes teams, number of wins, draws, losses, and points.

## Technologies Used
- Python 3
- Scrapy

## Installation
Make sure you have **Python** and **Scrapy** installed. If not, you can install them with the following command:

```bash
pip install scrapy
```

## How to Use
1. Clone this repository:
```bash
git clone https://github.com/mujahxd/espn-ucl-scraper.git
cd espn-ucl-scraper
```

2. Run the Scrapy spider:

```bash
scrapy runspider table.py -o table.json
```
