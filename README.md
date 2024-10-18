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

November 30, 2022 - Release of [ChatGPT](https://chatgpt.com/) by OpenAI with industry wide impact

March 31, 2023 - Release of [Gemini/Bard](https://gemini.google.com/app) by Google(GOOGL) 

November 1, 2023 - Release of [Copilot](https://copilot.microsoft.com/) + by Microsoft(MSFT)

### Output
The preformance was compared for total return for the time period and annualized return for time period and return from each event to the end and from total market from S&P500 for the same time period.

<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Total Returns</th>
      <th>Annualized Returns</th>
      <th>Total Returns (ChatGPT)</th>
      <th>Total Returns (Gemini)</th>
      <th>Total Returns (Copilot+)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>AAPL</th>
      <th>Close</th>
      <td>441.042627</td>
      <td>29.882271</td>
      <td>57.400528</td>
      <td>41.297761</td>
      <td>33.931137</td>
    </tr>
    <tr>
      <th>GOOGL</th>
      <th>Close</th>
      <td>209.072795</td>
      <td>21.534390</td>
      <td>64.224190</td>
      <td>59.886244</td>
      <td>31.158569</td>
    </tr>
    <tr>
      <th>MSFT</th>
      <th>Close</th>
      <td>400.639910</td>
      <td>28.192786</td>
      <td>68.652500</td>
      <td>49.254251</td>
      <td>24.339000</td>
    </tr>
    <tr>
      <th>FB</th>
      <th>Close</th>
      <td>215.533022</td>
      <td>26.201640</td>
      <td>384.707883</td>
      <td>170.095308</td>
      <td>83.562607</td>
    </tr>
    <tr>
      <th>S&amp;P 500</th>
      <th>Close</th>
      <td>113.756904</td>
      <td>13.287790</td>
      <td>41.233447</td>
      <td>40.229868</td>
      <td>35.976177</td>
    </tr>
  </tbody>
</table>
</div>


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
