# 📊 Financial Report Scraper

## Overview

This project is a web scraper designed to extract quarterly and annual financial reports from the press release feeds of three companies: Acousort, Carlsberg, and Stockwik. The scraper classifies and organizes the reports based on the correct quarter and year.

## Goal
The objective of this project was to:

- Extract press releases from each company's website.

- Classify the reports as quarterly or annual.

- Assign the correct quarter and year to each report.

## Technologies Used
- **Python** – Programming language
- **BeautifulSoup** – HTML parsing and data extraction
- **Requests** – HTTP requests to retrieve web content
- **Selenium** – Handling dynamic web content
- **Regex** – Pattern matching for extracting year and quarter
- **Pandas** – Data manipulation and organization

## Approach
### 1. **Acousort**
- Scraped the press release section.
- Filtered out relevant reports using keywords like `Q1`, `Q2`, `Q3`, `Q4`, `year-end`, and `financial`.
- Used regex to classify the reports by quarter and year.

### 2. **Carlsberg**
- Similar approach as Acousort.
- Extracted and filtered the press releases.
- Regex used to isolate reports related to financial statements.

### 3. **Stockwik**
- Dynamic content required handling using Selenium.
- Extracted press release links.
- Filtered and classified using regex.

## Challenges
###  **Acousort**
- No clear structure for identifying financial reports.
- Had to rely on keyword matching and regex.

### **Carlsberg**
- Press releases and financial statements were mixed.
- Regex was needed to isolate relevant links.

### **Stockwik**
- Website structure, making it harder to scrape static content.
- Used Selenium to handle dynamic content and extract data.

## Problems Solved
- Successfully classified reports into quarters and years.
- Managed dynamic content extraction using Selenium.
- Overcame inconsistent report structures using regex.

## Next Steps/Improvements
- Automate extraction at regular intervals.
- Improve regex for better classification.
- Expand to additional companies.


