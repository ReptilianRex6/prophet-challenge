# Prophet Challenge

## Introduction
This project aims to forecast trends using Prophet, a forecasting tool developed by Facebook. I utilized resources provided in the starter code from the following URLs:

* [Google Hourly Search Trends Dataset](https://static.bc-edx.com/ai/ail-v-1-0/m8/lms/datasets/google_hourly_search_trends.csv)
* [Mercado Stock Price Dataset](https://static.bc-edx.com/ai/ail-v-1-0/m8/lms/datasets/mercado_stock_price.csv)

I also inserted my own code to see the spike increase percentage 

```
spike_max = df_mercado_trends.loc['2020-05-05':'2020-05-06'].max()
norm_max = df_mercado_trends.loc['2020-05-07':'2020-05-31'].max()

# Calculate the percentage difference
(spike_max - norm_max) / norm_max * 100
```

I used GitHub Copilot to assist and explain the code to me. 
After doing what I could on Visual Studio Code, I moved onto Google Colab. From there, I had questions about some of the code, so I asked Colab AI for assistance. 
