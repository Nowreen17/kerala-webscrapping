# Kerala University Affiliated Colleges – Web Scraping Project

## 📌 Project Overview

This project focuses on collecting information about colleges affiliated with the University of Kerala using Python web scraping techniques. The data is extracted from the official university website, cleaned, organized, and analysed to generate useful insights.

## 🎯 Objectives

- Understand the structure of the university website.
- Extract college information using Requests and BeautifulSoup.
- Collect college names, addresses, contact numbers, email addresses, and website URLs where available.
- Clean and validate the extracted data.
- Store the data in CSV format.
- Perform exploratory data analysis and create visualizations.
- Identify useful insights from the collected dataset.

## 🌐 Data Source

**Website:** [University of Kerala – Affiliated Colleges](https://www.keralauniversity.ac.in/affiliated-colleges)

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- CSV
- Regular Expressions
- Matplotlib
- Jupyter Notebook

## 📂 Project Structure

```text
Kerala-University-Web-Scraping/
│
├── webscrapping.ipynb
├── webscrapping.py
├── kerala_university_colleges.csv
└── README.md
```

## 📊 Data Fields

The dataset is designed to contain the following fields:

| Column | Description |
|---|---|
| College Name | Name of the affiliated college |
| Address | College address, where available |
| District | District of the college, where available |
| College Type | Type of college, where available |
| Contact Number | College contact number, where available |
| Email Address | Official email address, where available |
| Website URL | College website, where available |

Missing information is left blank when it cannot be reliably extracted.

## ⚙️ Project Workflow

1. Connect to the university website using Requests.
2. Parse the webpage using BeautifulSoup.
3. Inspect HTML tags, classes, and links.
4. Extract available college information.
5. Organize the extracted data into a Pandas DataFrame.
6. Check for missing values and duplicate records.
7. Validate email addresses and contact numbers.
8. Export the dataset to a CSV file.
9. Generate summary statistics and visualizations.
10. Identify key findings and recommendations.

## 📈 Data Analysis

The project includes visualizations to explore:

- Colleges by district, when district data is available.
- Colleges with and without website URLs.
- Colleges with and without email addresses.
- Distribution of college types.
- Availability of college contact information.

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Navigate to the project folder

```bash
cd Kerala-University-Web-Scraping
```

### 3. Install the required libraries

```bash
pip install requests beautifulsoup4 pandas matplotlib jupyter
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open `webscrapping.ipynb` and run the cells in order.

Alternatively, run the Python script:

```bash
python webscrapping.py
```

## 🔍 Expected Outcomes

- A structured dataset of affiliated colleges.
- A CSV file containing the extracted information.
- A summary of missing and duplicate records.
- Visualizations of college information.
- Key findings and recommendations based on the collected data.

**Note:** The completeness of the dataset depends on the information available on the source website and the effectiveness of the extraction process. Contact information may require visiting individual college websites.

## 👩‍💻 Author

**Project:** Kerala University Affiliated Colleges – Web Scraping

**Purpose:** Educational assignment on web scraping, data collection, data cleaning, and exploratory data analysis.
