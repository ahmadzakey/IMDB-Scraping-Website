# IMDB Top 100 Web Scraping Project

## Project Overview
This project focuses on web scraping data from [IMDB's Top 100 movies](https://www.imdb.com/search/title/?groups=top_100) using **BeautifulSoup** and **Requests**. The goal is to extract movie details and save them in an organized format for further analysis.

## Why Web Scraping?
Web scraping allows us to gather data from websites when APIs are unavailable or inaccessible. In this project, I opted for **BeautifulSoup** and **Requests** over **Selenium** due to their lightweight nature and faster execution. Selenium, however, is useful for extracting JavaScript-loaded data that Requests cannot access directly.

### Alternative Methods:
- **Selenium:** Useful when dealing with dynamically loaded content.
- **APIs:** A cleaner and structured way to extract data (I have yet to explore API-based data extraction).

## Data Extraction Details
- **Total Data Scraped:** 25 movies
- **Extracted Features:** (e.g., Title, Rating, Year, Genre, Director, Cast)
- **Output Format:** Saved as an **Excel file** for easy analysis.

## Tools & Libraries Used
- **Python**
- **BeautifulSoup** (HTML parsing)
- **Requests** (Fetching website content)
- **Pandas** (Data processing & saving to Excel)

## Next Steps
- Expand scraping to extract **all** Top 100 movies.
- Explore API-based data extraction for cleaner data.
- Perform data visualization using **Matplotlib** & **Seaborn**.

## Repository Structure
```
📂 IMDB_Scraping_Project
├── 📂 Data
│   ├── imdb_top_25.xlsx  # Extracted dataset
├── 📂 Notebook
│   ├── Analysis.ipynb    # Jupyter notebook with analysis
├── README.md             # Project documentation
```

## Author
**Ahmad Zaki Bin Ramli**  
📧 [zakey53319@gmail.com](mailto:zakey53319@gmail.com)  
🔗 [GitHub](https://github.com/ahmadzakey)
