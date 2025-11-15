# Rang_Dong_webscraping

# 📝 Overview
This project automates the process of collecting product data from the Rang Dong website and storing it in a structured database. Through these data, we also made an interactive dashboard for a deeper understanding and analysis of Rang Dong's products.

# 🚀 Features
- **Web Scraping**: Automatically extracts product information (names, categories, specifications, pricing, etc.) from the Rang Dong website.
- **Data Cleaning & Structuring**: Normalizes raw HTML data into clean, consistent tables.
- **Database Creation**: Stores processed data in a relational database for easy querying and scalability.

# 📁 Repository Structure
```
├── Dashboard/
|   ├── Rang_Dong_dashboard.pbix
|
├── Database/
|   ├── categories.csv
|   ├── products.csv    
|   ├── rangdong.db
|  
├── Scraping/
|   ├── product_links.csv    
|   ├── Rang Dong Scraping.ipynb
```

# 🧰 Tech Stack
- **Python**: Data scraping, cleaning, and automation
- **BeautifulSoup / Selenium**: HTML parsing
- **Pandas**: Data transformation
- **SQL (SQLite/MySQL)**: Persistent data storage
- **Power BI / Tableau / Streamlit**: Dashboard visualization

# How to Run the Project
## 1. Clone the repository
Clone the repository from Github:
```bash
git clone https://github.com/PhamMaiLinh-2403/Rang_Dong_webscraping.git
```
## 2. Create environment & Install dependencies 
Create a virtual environment and install necessary packages:
```bash
conda create --name <your_env>
conda activate <your_env>
cd <your_dir>
pip install -r requirements.txt
```
With `<your_env>` being your environment's name and `<your_dir>` being the directory that you have cloned the repository into
## 3. Run the code
We store all the code in a .ipynb file. With the previously created environment, you can run the code to extract data and transform them. The .ipynb file can be found in the `\Scraping` directory.

# 📈 Results
By completing this workflow:
- You automated data collection from a commercial product website
- Built a reusable database for structured analytics

# 📌 Future Improvements
- Add scheduling for automatic daily/weekly scraping
- Implement API endpoints for other applications to query the database
- Integrate machine learning for product clustering or price trend prediction
