# 💻 Laptop Market Analysis using Web Scraping & Python EDA

## 📌 Overview

The **Laptop Market Analysis** project is an end-to-end data analytics project that collects laptop product information from **Flipkart** using **web scraping**, preprocesses the data, and performs **Exploratory Data Analysis (EDA)** to identify pricing patterns, brand performance, and hardware trends.

The project demonstrates the complete data analytics lifecycle:

**Web Scraping → Data Cleaning → Exploratory Data Analysis → Data Visualization → Business Insights**

---

# 🎯 Objectives

* Collect laptop data from Flipkart using web scraping.
* Build a structured dataset for analysis.
* Clean and preprocess the collected data.
* Perform Exploratory Data Analysis (EDA).
* Visualize market trends and customer preferences.
* Generate business insights to support purchasing and market analysis.

---

# 📂 Dataset

**Source:** Flipkart

**Collection Method:** Web Scraping using BeautifulSoup and Regular Expressions (Regex)

**Dataset Size:** **2,000+ Laptop Listings**

### Dataset Features

* Brand
* Laptop Name
* Price
* Processor
* RAM
* Storage
* Graphics Card
* Display Size
* Operating System
* Customer Rating
* Number of Ratings
* Product URL

---

# 🛠️ Tech Stack

* Python
* Google Colab
* BeautifulSoup
* Requests
* Regular Expressions (Regex)
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# 📁 Project Structure

```text
Laptop-Market-Analysis/
│
├── Laptop_Market_Analysis.ipynb
├── Scraped_Data.xls
├── Cleaned_Data.xls
├── README.md
├── requirements.txt
└── images/
    ├── price_distribution.png
    ├── brand_analysis.png
    ├── correlation_heatmap.png
    ├── processor_analysis.png
    └── ram_vs_price.png
```

---

# 🔄 Project Workflow

### 1. Web Scraping

* Scraped **2,000+ laptop listings** from Flipkart.
* Used **Requests** to retrieve web pages.
* Parsed HTML using **BeautifulSoup**.
* Used **Regex** to clean price and specification data.
* Stored the extracted information in a CSV dataset.

### 2. Data Preprocessing

* Removed duplicate records.
* Handled missing values.
* Converted data types.
* Cleaned text columns.
* Extracted useful features for analysis.

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

* Laptop Price Distribution
* Brand-wise Laptop Count
* Average Price by Brand
* Processor Comparison
* RAM Distribution
* Storage Analysis
* Customer Ratings
* Graphics Card Analysis
* Price vs RAM
* Price vs Processor
* Correlation Heatmap
* Outlier Detection

### 4. Data Visualization

Created visualizations using:

* Bar Charts
* Count Plots
* Histograms
* Box Plots
* Scatter Plots
* Pie Charts
* Correlation Heatmaps

---

# 📊 Key Business Insights

* Collected and analyzed **2,000+ laptop listings** from Flipkart.
* Apple and premium gaming brands occupied the highest price range.
* Laptops with **Intel Core i7/i9** and **AMD Ryzen 7/9** processors generally had higher prices.
* Devices with **16GB+ RAM** and **SSD storage** were priced significantly higher than entry-level configurations.
* Dedicated GPU laptops were concentrated in the premium segment.
* Mid-range laptops represented the largest share of available products.
* SSD storage was the most common storage type across brands.
* Customer ratings showed that premium laptops generally maintained strong user satisfaction.

---

# 📈 Skills Demonstrated

* Web Scraping
* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Python Programming
* Statistical Analysis

---

# ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/Laptop-Market-Analysis.git
```

### Open the Project

Open **Laptop_Market_Analysis.ipynb** using:

* Google Colab
* Jupyter Notebook

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Execute all notebook cells sequentially to:

* Scrape laptop data
* Generate the dataset
* Clean and preprocess the data
* Perform EDA
* Create visualizations
* Generate business insights

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
beautifulsoup4
requests
lxml
```

---

# 🚀 Future Enhancements

* Automate daily laptop price tracking.
* Build an interactive Power BI dashboard.
* Develop a Streamlit web application.
* Integrate data from multiple e-commerce platforms.
* Build a machine learning model for laptop price prediction.

---

# 📸 Sample Visualizations

* Price Distribution
* Brand-wise Laptop Count
* Average Price by Brand
* Processor Analysis
* RAM Distribution
* Storage Analysis
* Correlation Heatmap
* Price vs RAM Scatter Plot

---

# 👨‍💻 Author

**Sujith Karnati**

* B.Tech (AI & ML)
* Python Developer
* Data Analyst
* SQL & Power BI Enthusiast

---

## ⭐ If you found this project helpful, consider giving it a Star!
