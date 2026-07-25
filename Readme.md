# Exploratory Data Analysis (EDA) on Smart TV Market Data

## 📌 Project Overview
This repository contains an **Exploratory Data Analysis (EDA)** project focused on the Smart TV market. Smart TV buyers often struggle to evaluate whether price differences across models reflect actual hardware quality or brand markups, technical jargon (e.g., OLED, QLED, 4K, 8K, HDR), and varying display technologies. 

Using data web-scraped from **Poorvika**, this project analyzes pricing drivers, feature premium impacts, and value-for-money metrics across various Smart TV brands, resolutions, and screen sizes.

## 🎯 Business Problem & Objectives

### Business Scenario (Customer Persona: Ananya)
Ananya is shopping for a 55-inch 4K Smart TV. She encounters options priced at **₹35,000** and **₹65,000**, both labeled "4K UHD". She wants to determine whether paying the additional ₹30,000 provides tangible hardware/picture quality improvements or if she is merely paying for a brand logo.

### Key Business Questions
1. **The Resolution Premium:** Is paying extra for 4K or 8K resolution worth the investment for average consumers?
2. **Feature Impact:** How significantly do screen size, display technology, and resolution drive final retail prices?
3. **Price Drivers:** Which technical features (e.g., OLED vs. QLED vs. LED, Brand, Resolution) genuinely increase pricing?
4. **Value for Money:** Which Smart TVs provide the best **Price-per-Inch** ratio for budget-conscious buyers?
5. **Brand Bias vs. Hardware Value:** Are higher prices driven by brand premium or actual hardware upgrades?

## 🛠 Tech Stack & Dependencies

### Libraries Used
* **Language:** Python 3.8+
* **Web Scraping:**- requests, beautifulsoup4, regex
* **Data Processing:** pandas, numpy
* **Visualization:** matplotlib, seaborn

### requirements.txt**
requests>=2.28.0
beautifulsoup4>=4.11.0
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
notebook>=6.5.0

## project files
├── Smart_TV_EDA_Pipeline.py   # Complete Standalone Execution Script (Scraping + Preprocessing + EDA)
├── Smart_TV_EDA.ipynb        # Interactive Jupyter Notebook Analysis
├── requirements.txt          # Project Dependencies
└── README.md                 # Documentation

## clone the repository

git clone https://github.com/Baddampravallika/.git

## set up a virtual enviroment

# for linux/macos
python3 -m venv venv 
source venv/bin/activate

##  for windows

python -m venv venv
venv\Scripts\activate

## install required libraries

pip install -r requirements.txt

## launch via interactive jupyter notebook
jupyter notebook Smart_TV_EDA.ipynb
