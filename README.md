# Facebook Scraping with Selenium & MongoDB

This repository contains a **technical exercise** where I implemented a web scraping script to collect Facebook posts, comments, and images.  
The data is stored in **MongoDB** for further analysis.

## Features
- Automated login to Facebook (using Selenium WebDriver)
- Search for specific keywords (e.g., "décès du président Jacques Chirac")
- Scrape posts, authors, timestamps, comments, and images
- Store scraped data into MongoDB
- Avoid duplicate entries
- Stop after a configurable number of posts (default: 20)

## Technologies Used
- **Python**
- **Selenium**
- **BeautifulSoup**
- **MongoDB (pymongo)**
- **ChromeDriver**

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/ManelHjaoujia/facebook-scraping-mongodb.git
