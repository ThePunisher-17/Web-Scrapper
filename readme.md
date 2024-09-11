# Web Scraper

## Overview
This project is a web scraping tool designed to extract data from websites and store it in a structured format. It is perfect for developers, researchers, and data enthusiasts who need to collect large amounts of data from web pages.

## Features
- **Recursive URL Crawling**: Intelligently traverses websites to discover and scrape linked pages.
- **Configurable Depth**: Set the maximum depth for URL recursion to control the scope of your scraping.
- **Smart URL Filtering**: Include or exclude URLs based on keywords or prefixes.
- **Organized Output**: Automatically creates a directory structure based on the domain being scraped.
- **Respectful Scraping**: Implements user-agent rotation and retry logic with exponential backoff to respect website policies.
- **Highly Configurable**: Easy-to-use configuration file for customizing scraping behavior.
- **Text Splitting**: Automatically splits long texts into smaller chunks to avoid metadata size limits.
- **Protocol Exclusion**: Easily exclude specific protocols (e.g., WhatsApp, tel, mailto) from scraping.
- **Flexible Retry Mechanism**: Configurable maximum retries and base delay for failed requests.
- **Concurrent Request Control**: Set limits on concurrent requests and connections per host.
- **Request Pacing**: Configurable delay between individual requests to prevent overwhelming target servers.

## Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

## Installation and Setup
1. Clone this repository:
    ```sh
    git clone https://github.com/ThePunisher-17/Web-Scrapper.git
    ```
2. Change to the project directory:
    ```sh
    cd web-scrapper
    ```
3. (Optional but recommended) Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the scraper and its dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
After installation, you can run the scraper from the project directory:
```sh
python app.py

