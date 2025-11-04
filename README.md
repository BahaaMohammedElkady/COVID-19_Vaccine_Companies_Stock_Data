# COVID-19 Vaccine Companies Stock Analysis

## Project Overview
This project analyzes the stock performance of major pharmaceutical companies during the COVID-19 pandemic era, focusing on both next-generation technology companies and established pharmaceutical firms. The analysis covers the period from October 2019 onwards, examining market valuation, returns, volatility, and the impact of key pandemic-related events.

## Dataset
The analysis uses stock market data for eight major pharmaceutical companies:

### Next-Gen Technology Companies
- BioNTech
- Moderna
- Inovio Pharmaceuticals
- Novavax

### Established Pharmaceutical Companies
- Johnson & Johnson
- AstraZeneca
- Sinovac
- Sinopharm

The dataset (`vaccine stocks.csv`) includes daily stock price information:
- Open, High, Low, Close prices
- Adjusted Close prices
- Trading Volume

## Analysis Components

### 1. Data Preparation & Cleaning
- Date standardization and indexing
- Missing value handling
- Data validation and quality checks

### 2. Exploratory Data Analysis (EDA)
- Normalized price analysis
- Trading volume patterns
- Basic statistical measures

### 3. Performance Metrics
- Daily and cumulative returns
- Volatility calculations
- Risk-adjusted performance measures (Sharpe Ratio)

### 4. Event Analysis
Key events analyzed include:
- WHO pandemic declaration (March 11, 2020)
- Vaccine trial announcements
- Emergency Use Authorizations (EUAs)
- Other significant company-specific events

### 5. Comparative Analysis
- Next-Gen vs. Established companies performance
- Correlation analysis
- Risk-return profiles

## Key Findings

1. **Returns Performance**
   - Next-gen companies significantly outperformed traditional pharmaceuticals
   - Highest returns: Novavax, followed by Moderna and BioNTech
   - Established companies showed more stable but lower returns

2. **Risk Analysis**
   - Higher volatility in next-gen companies
   - Lower but stable returns in established companies
   - Clear risk-return tradeoff between the two groups

3. **Event Impact**
   - Significant market reactions to vaccine development news
   - Volatility spikes around major announcements
   - Different response patterns between company groups

## Tools Used
- Python 3.x
- Key Libraries:
  - pandas: Data manipulation and analysis
  - numpy: Numerical computations
  - matplotlib: Data visualization
  - seaborn: Statistical visualizations
  - plotly: Interactive visualizations

## Getting Started

### Prerequisites
- Python 3.x
- Required Python packages:
```
pandas
numpy
matplotlib
seaborn
plotly
```

### Installation
1. Clone this repository
2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn plotly
```

### Running the Analysis
1. Open `COVID19_Vaccine_Stocks_Analysis.ipynb` in Jupyter Notebook or VS Code
2. Ensure `vaccine stocks.csv` is in the `Datasets` directory
3. Run all cells in the notebook

## Repository Structure
```
COVID-19_Vaccine_Companies_Stock_Data/
│
├── COVID19_Vaccine_Stocks_Analysis.ipynb   # Main analysis notebook
├── README.md                               # Project documentation
│
└── Datasets/
    └── vaccine stocks.csv                  # Stock market data
```

## Investment Recommendations
The analysis includes detailed investment recommendations covering:
- Portfolio allocation strategies
- Risk management approaches
- Long-term investment considerations
- Market monitoring guidelines

## Contributors
- [Your Name/Organization]

## License
This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments
- Data sources
- Research references
- Analytical methodology references