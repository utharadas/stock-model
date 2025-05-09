# stock-market-analysis

<table>
<tr>
<td>
This project explores trends, volatility, and behavioral patterns in the stock market using historical data from companies listed in the S&P 500 index. Our initial project idea focused on analyzing weather and traffic data, but we pivoted after facing limitations with dataset availability and size. Using this more accessible and robust stock dataset, we applied exploratory data analysis and basic statistical modeling to investigate trade volume patterns, extreme price changes, and dynamic relationships between price and volume.
</td>
</tr>
</table>

## File Structure

- **final_project_stock.ipynb** – Main notebook with data cleaning, exploratory data analysis, and visualizations, including top traded stocks, price volatility, and rolling correlations. Contains unsupervised learning or classification tasks to group stock behaviors.

## Dataset

S&P 500 stock market data including daily open, close, high, low prices, and trade volume for each listed company over several years.

[*Note: Dataset sourced from Kaggle.*](https://www.kaggle.com/datasets/camnugent/sandp500)

## 🔧 Built With

- [pandas](https://pandas.pydata.org/) – For data cleaning and manipulation  
- [matplotlib](https://matplotlib.org/) – For creating custom static visualizations  
- [seaborn](https://seaborn.pydata.org/) – For generating insightful statistical plots  
- [numpy](https://numpy.org/) – For efficient numerical operations  

## Key Insights

- Identified the top 10 most actively traded stocks based on average volume  
- Detected extreme daily price changes and increased volatility in certain stocks after 2016  
- Visualized rolling 30-day correlations between price and volume to show dynamic market behavior

## Future Work

- Add external data to explain volatility  
- Cluster stocks by behavior over time using unsupervised learning  
- Test predictive models for next-day price movement or volatility classification  

## Team

- Duraid Syed
- Merna Mostafa
- Uthara Das
