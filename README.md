# LinkedIn Job Scraper

This project scrapes job listings from LinkedIn, classifies them into relevant job categories, and visualizes the distribution of job roles. 
The goal is to gather structured job market insights using Python-based web scraping and data analysis.

## 📌 Features

- Scrapes job data (title, company, location, link) from LinkedIn listings.
- Automatically classifies job titles into categories and subcategories.
- Filters out incomplete or masked job data.
- Saves structured data to a CSV file.
- Generates a bar chart visualizing job role distributions.

## 🧰 Technologies Used
- Python
- `requests` – for making HTTP requests
- `BeautifulSoup` – for parsing HTML
- `csv` – for saving structured job data
- `pandas` – for data manipulation
- `matplotlib` – for visualization

## 🗃️ Output

- **new_linkedin_job.csv**: Contains structured job listings with classification.
- **Bar chart**: Shows number of job postings by sub-category.

  
## 🧠 Job Classification Logic

The scraper uses keyword-based classification for the following categories:
- Software & IT
- Data & Analytics
- Marketing & Sales
- Finance & Banking
- Healthcare
- Human Resources
- Design & Creative
- Operations & Admin
- Legal

Each category includes various subcategories like "Frontend Developer", "Data Scientist", "Sales Manager", etc.

## ▶️ How to Run

1. Clone the repository or open the Jupyter notebook.
2. Run the code in a Python environment with required libraries installed.
3. The script will:
   - Scrape job listings from LinkedIn (New Delhi by default)
   - Save the results in `new_linkedin_job.csv`
   - Plot a bar chart of sub-category job distribution

> ⚠️ Note: Web scraping from LinkedIn may be rate-limited or blocked. Use with caution and respect their `robots.txt` and TOS.

## 📈 Output

- A CSV file like:
![Screenshot 2025-04-22 192039](https://github.com/user-attachments/assets/f88aace7-ab00-4056-b13d-4e38594f9e4c)


- A visual chart like:
- ![Screenshot 2025-04-22 180900](https://github.com/user-attachments/assets/16465a3f-d60d-43b4-bcc8-64a1b79b6636)


## 📬 Contact
Made with ❤️ by Deeksha Singh 📧 deeksha25022004@gmail.com
For suggestions or questions, feel free to open an issue or get in touch.

