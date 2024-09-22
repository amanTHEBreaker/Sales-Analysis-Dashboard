

# Patanjali Outlet Sales Analysis

This project focuses on scraping data from various outlets to extract information on special products and their associated reviews. Additionally, it includes a predictive analysis of outlet sales using a dataset provided by Kaggle, specifically for Patanjali products.

## Project Overview

The goal of this project is twofold:
1. **Scraping and Analysis**: Collect data from various outlets on special products, including reviews and product features.
2. **Sales Prediction**: Use the provided dataset to predict outlet sales using machine learning models.

### Data Source

The primary dataset used for sales prediction is obtained from the [Patanjali Kaggle Dataset](https://www.kaggle.com). This dataset includes information about various products sold through outlets, along with details on outlet characteristics and sales history.

## Key Features

1. **Data Scraping**:
   - Scraped data from multiple online retail outlets to extract details on products and their reviews.
   - Special focus on unique and featured products.

2. **Sales Prediction**:
   - Predicted outlet sales using features such as item type, fat content, outlet size, and outlet type.
   - Implemented multiple machine learning algorithms to build and optimize predictive models.

3. **Visualization**:
   - Created visual dashboards using Power BI to represent:
     - Outlet sales trends by outlet type and size.
     - Product distribution by fat content and type.
     - Overall sales distribution across different outlets.

## Tools and Technologies

- **Data Scraping**: BeautifulSoup, Requests
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Visualization**: Power BI
- **Dataset**: Patanjali Kaggle dataset

## Installation and Usage

### Prerequisites

- Python 3.x
- Required Python libraries: BeautifulSoup, requests, pandas, numpy, scikit-learn
- Power BI Desktop for visualization (optional)

### Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/patanjali-outlet-sales-analysis.git
   cd patanjali-outlet-sales-analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Data Scraping**:
   - The script for scraping outlet data can be run using:
     ```bash
     python scrape_outlets.py
     ```

4. **Run Sales Prediction**:
   - Train and evaluate models for sales prediction using:
     ```bash
     python sales_prediction.py
     ```

5. **Visualization**:
   - The Power BI `.pbix` file can be opened in Power BI Desktop for an interactive dashboard view.

## Results

The results of the analysis, including sales predictions and trends across different outlets, are documented in the final report. 

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for review.

