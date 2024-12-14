# Google Trends Data Analysis

This project explores how search trends on Google relate to real-world data, such as stock prices, cryptocurrency trends, and unemployment rates. The analysis uses data from Google Trends and compares it to various datasets, including Tesla stock prices, Bitcoin prices, and unemployment rates in the U.S.

---

## Data Sources

- [Unemployment Rate from FRED](https://fred.stlouisfed.org/series/UNRATE/)
- [Google Trends](https://trends.google.com/trends/explore)
- [Yahoo Finance for Tesla Stock Price](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)
- [Yahoo Finance for Bitcoin Stock Price](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

---

## Project Features

### Data Exploration

1. **Tesla Data**

   - Analyze Tesla's search trend data and compare it with Tesla's stock price.
   - Explore data shapes, columns, and descriptive statistics.
   - Investigate the periodicity of the time series data.

2. **Unemployment Data**

   - Compare search trends for "Unemployment Benefits" with the actual unemployment rate in the U.S.
   - Identify seasonal patterns and trends.

3. **Bitcoin Data**
   - Analyze the relationship between Bitcoin search volume and its price.
   - Examine trends and key spikes in data.

### Data Cleaning

- Handle missing values by identifying and removing them.
- Convert string-based date columns into `datetime` objects.
- Aggregate daily data into monthly summaries for a clearer analysis.

### Data Visualization

1. **Tesla Stock Price vs. Search Volume**

   - Dual-axis line chart comparing Tesla's stock price and search volume.
   - Customizable plot styles for clarity and aesthetics.

2. **Bitcoin Price vs. Search Volume**

   - Compare Bitcoin's price and search trends using line and marker styles.
   - Investigate if price changes coincide with search spikes.

3. **Unemployment Benefits vs. Unemployment Rate**
   - Explore the correlation between search trends and unemployment rate.
   - Use rolling averages to identify lead-lag relationships in trends.

---

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `matplotlib`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/dhingra30/google-trends-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd google-trends-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage

1. Download the required `.csv` files and place them in the same directory as the notebook.
2. Follow the instructions in the notebook to explore, clean, and visualize the data.
3. Customize visualizations and analyses to your needs.

---

## Key Questions Explored

- Does search popularity on Google relate to stock prices or economic indicators?
- Can spikes in search terms like "Unemployment Benefits" predict real-world outcomes?
- What patterns exist in Google Trends data for Tesla, Bitcoin, and unemployment?

---

## Contributions

Contributions are welcome! If you'd like to improve the code or add more datasets to analyze, please:

1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.
