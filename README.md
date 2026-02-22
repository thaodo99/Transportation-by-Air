<a name="top"></a>
# ✈️ BAIT 508 Group Project — Transportation by Air (SIC 45)

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [How To Use](#how-to-use)
- [Installation](#installation)
- [Analysis Workflow](#analysis-workflow)
- [References](#references)
- [Author Info](#author-info)

  
## Description

This project analyzes firms in the Transportation by Air industry (SIC codes starting with 45) using both structured financial data and unstructured 10-K business descriptions.
The objective is to understand:
- Industry composition and geographic distribution
- Historical stock price trends
- Impact of the 2008 Financial Crisis
- Key business themes extracted from Item 1 (“Business”) sections of 10-K filings
- Deliverables include exploratory financial analysis, time-series visualization, and text analytics (TF-IDF + word clouds) to surface dominant sector topics.

This work was completed as a group project for BAIT 508 – Business Applications of AI & Text Analytics.

[Back To The Top](#top)

### Technologies

- Python
- pandas / numpy
- matplotlib
- scikit-learn (TF-IDF)
- wordcloud

[Back To The Top](#top)

## How To Use

### Installation
```bash
pip install pandas numpy matplotlib scikit-learn wordcloud
```

### Run the Analysis
1. Place datasets in the appropriate folders:
- data/public_firms.csv
- 10-K Item 1 text files (e.g. 2020_10K_item1_full.csv)

2. Open the notebook or exported HTML.

3. Run cells top-to-bottom to reproduce:
- Sector filtering (Transportation by Air only)
- Descriptive financial analysis
- Stock price trend visualization
- 2008 crisis impact calculation
- Keyword extraction + TF-IDF
- Word cloud generation

[Back To The Top](#top)

### Analysis Workflow
- Filter firms by SIC code (Transportation by Air)
- Perform exploratory analysis on price, sales, and geography
- Compute historical stock trends and crisis impact
- Clean Item 1 text data
- Apply TF-IDF to extract dominant keywords
- Visualize themes using word clouds

[Back To The Top](#top)

### References
- W3Schools – Python string methods
- W3Schools – pandas filtering utilities
- Course materials (BAIT 508)

[Back To The Top](#top)

### Author Info
- Thao Do, Koko Deng (UBC)

[Back To The Top](#top)
