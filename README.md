Naukrigulf Job Scraper 🕷️📊

-->An automated Python-based web scraping project designed to extract job listing data from Naukrigulf. This scraper targets the first 3 pages of search/category results and gathers essential job information into a structured format for data analysis or storage.

📌 Extracted Data Fields 

For each job post, the scraper extracts the following attributes:

Job Title 

Company Name 

Location

Experience Required (in years)

Job Description 


🛠️ Tools & Technologies

Python 3.x

Selenium 

Pandas (For exporting to CSV)

Time (So that it can collect and load the data)


⚙️ How It Works 

URL Targeting: The script iterates through the first 3 pagination pages of Naukrigulf search results.

HTML Parsing: HTML elements containing job cards are parsed using CSS Selectors / Class Name.

Data Extraction: Extracts specific details (Title, Company, Location, Experience, and Description) from each job card or individual detail page.

Data Export: Saves the gathered dataset into a CSV file format for further use
