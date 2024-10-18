Project1_Group3
Project one group three consolidates lessons from modules 1-9. 

## Project Description

##### Team members 

Alexander Iruthaya, Aannd Bhagwat, Cameron Burgess, Jean Clark, Usha Hariharan

### Project Objectives

We are interested in learning more about a possible correlation between a company's AI initiatives and it's stock price and market valuation relative to overall market trends.

**Hypothesis: AI has signifigantly impacted the stock values and trading volumes for companies with AI development focus.** 

### Scope

Selected a time frame January 1, 2018 to October 1, 2024 and data files from four key companies.
The following companies data were selected for the analysis and compared against the S&P500.

**Apple(AAPL), Google(GOOGL), Microsoft(MSFT), Facebook/META(META)**
 
### Input

1697 data points collected for each stock for the time period defined above in the scope. 

### Major Events selected for Segmented Analysis

November 30, 2022 - Release of ChatGPT by OpenAI with industry wide impact

March 31, 2023 - Release of Gemini/Bard by Google(GOOGL) 

November 1, 2023 - Release of Copilot + by Microsoft(MSFT)

### Output
The preformance was compared for total return for the time period and annualized return for time period and return from each event to the end and from total market from S&P500 for the same time period.

### Notes 

### Installation Instructions 

Prerequisites needed 
```
!pip install prophet
!pip install yfinance
# Dependencies
import pandas as pd
import os
from datetime import datetime
from pathlib import Path
%matplotlib inline
import matplotlib.pyplot as plt
import numpy as np
import yfinance as yf
```
---

## Added csv files and pulled individual stock data and S&P 500 index
## Google launched GEMINI - the AI chatbot - on March 31, 2023
## Microsoft lauched Copilot+ on November 1, 2023

Added revised csv datasets from YahooFinance
Worked on Data exploration and analysis

###### Data References 
- [yahoo finance](https://finance.yahoo.com/)

- [Kaggle (for S&P500)](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks)
