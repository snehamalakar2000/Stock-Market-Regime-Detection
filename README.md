# Stock-Market-Regime-Detection for NASDAQ and S&P 500

Applied the Hidden Markov Model (using GaussianHMM) to the following datasets using python libraries: Pandas, Numpy and Plotly. 
(CLICK ON LINK TO SEE RESULT GRAPHS)
- Daily asset price data for S&P 500 (https://colab.research.google.com/drive/1zjNFSlmxPQgcOWtwkANo1ggCrBlT2EZb?usp=sharing)
- Daily asset price data for NASDAQ (https://colab.research.google.com/drive/1mklhXK-TLIqZR1qc1xXmvPgRUj6DqBEK?usp=sharing)

Methodology: 
- The adjusted closing price moving average of 7 days was calculated and based on that, the adjusted closing price log return was determined.
- Hidden Markov Model applied to the data where hidden states are the market regimes and observable data are the log return prices.
- Compared market regime distribution in the following three periods:
  1) The Great Depression (2008)
  2) COVID – 19
  3) Recent Economic Distress 2023

The Hidden Markov Model: 
The Hidden Markov Model is a mathematical model that is used to analyze time-series data. It works to detect hidden states based on observable data. It runs on the assumption that hidden states change over time according to a Markov Process. The Markov Process is the assumption that the state you are in today solely depends on the state you were in yesterday. Each hidden state corresponds to a different Gaussian distribution in the observable data.

Conclusion: 
- Based on the findings presented above, it can be concluded that the S&P 500 and NASDAQ exhibit distinct market regimes during certain time periods, as evidenced by their diverging performance during the COVID-19 pandemic and the recent economic distress of 2023.
- Notably, the NASDAQ index, which primarily comprises technology companies, underperformed the overall market during these periods, suggesting a possible correlation between industry and market regimes.
- These results emphasize the potential benefits of considering industry-specific indexes when formulating investment strategies, as such analysis may offer valuable insights into the dynamics of different market sectors and enable more informed decision-making.

