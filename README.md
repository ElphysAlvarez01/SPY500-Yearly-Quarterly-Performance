# S&P500- A Yearly & Quarterly Performance Analysis
These analyses examine yearly and quarterly market performance trends over multiple decades, identifying key patterns and anomalies.
The series of analyses conducted are: 

### Description: 

### Practical Application: 

### Data Source:
- **yFinance:** S&P 500 (Ticker: SPY) data was fetched with Yahoo finance API. Only basic historical price (Open Price, High Price, Low Price, Close Price) and Volume information were retrieved with a start date of 1995-01-01. 

### Libraries used:
| **Category**                | **Libraries/Tools**                                                |
|-----------------------------|--------------------------------------------------------------------|
| **Data Handling and Manipulation** | Pandas, Numpy, DateTime, Timedelta                                    |
| **Visualization**           | Plotly Express, Plotly Graph Objects, Make_subplots, Matplotlib.pyplot |

>> **Note:** I prefer to keep it consistent and only use one Viz library. However, there were some charts difficult to complete with Plotly.

### Series of Analyses:
#### **Section 1: *Feature Engineering & Basic Statistical Exploratory Analysis*:**
#### **Feature Engineering:** 
The table below summarizes the transformation of the original dataset to include yearly metrics, grouped by category, along with descriptions.

| **Category**             | **Fields**                                                                                                   | **Description**                                                                                                                                                                  |
|--------------------------|-------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Original Data**        | Open, High, Low, Close, Volume                                                                              | Reflects the initial dataset fields.                                                                                                                                           |
| **Price Information**    | Average Open, Average High, Highest High, Lowest Low, Start Price, End Price                                | To summarize the year, price metrics were averaged to summarize the year, and a "Start Price" and "End Price" were created.                                                    |
| **Volume Metrics**       | Average Volume, Highest Volume Day, Lowest Volume Day                                                      | Similarly to price metrics, volume data was summarized for the year as well.                                                                                                   |
| **Standard Deviation**   | Q1 Std Dev, Q2 Std Dev, Q3 Std Dev, Q4 Std Dev, Annual Std Dev                                             | Captures variability in data over different time frames (quarterly and annual). In the markets, standard deviation reflects volatility, indicating the range of price movements. |
| **Performance Metrics**  | Q1 Performance, Q2 Performance, Q3 Performance, Q4 Performance, Yearly Performance (%)                     | Tracks performance over quarters and annually.                                                                                                                                 |
| **Price Analysis**       | Price Range, Price Difference                                                                              | Includes derived metrics such as price range and differences to understand price movement strength.                                                                             |

**Yearly & Quarterly Performance:**


#### **Section 2: *Unexpected Volume Insights*:**

**Where did the Volume go?"**

#### **Section 3: *Highlighting Extraordinary Yearly Performance*:**

**Market Optimism Clusters Together:**

#### **Section 4: *Yearly Performance & Annual Std Dev Correlation*:**

**Does Volatility Influence Performance?"**


### Conclusion:

### Next Steps:
