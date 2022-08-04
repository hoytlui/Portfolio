# My Portfolio

- [Resume](https://www.dropbox.com/s/0r3m9xaepft2pog/Hoyt%20Lui%20Resume.pdf)
- [LinkedIn](https://www.linkedin.com/in/hoytlui/)
- [Personal website](https://www.hoytlui.com)

## [Stock Selection Model](https://github.com/hoytlui/Stock-Selection-Model)
- Downloaded stock data such as symbols, currency, sector, company name, stock price, etc
- Built program through data manipulation and visualization to create strategies and backtest performance based on stock trading and financial knowledge
<img src="https://github.com/hoytlui/Stock-Selection-Model/blob/main/Images/technical_analysis_TSLA_2y.png" width=800>

## [News Classification with Natural Language Processing and Deep Learning](https://github.com/hoytlui/News-Classification-NLP-Deep-Learning)
- Downloaded financial news data from one of the Kaggle datasets
- Applied deep learning and NLP to classify news into 7 types (Redundant/meaningless, Analyst action, Earnings, Corporate action, Merger and acquisition, Company guidance, Options) through 2 models - rules-based and manually-labelled
- Preprocessed data using tokenization to break down text strings into chunks of words, then converted words into sequences of integers using sequence padding
- Implemented sequential model along with features like 1) pooling layers to summarize the presence of features in the patches of the feature map, and 2) early stopping to reduce overfitting the model
- Recommended manually-labelled model and suggested ways of improvement for a more sophicated model
<img src="https://user-images.githubusercontent.com/36130927/127268161-eed6b8c0-e15e-4a1f-a7a3-23a6d19783f9.png" width=600>

## [GDP Growth Forecast with Multivariate Time Series Analysis](https://github.com/hoytlui/GDP-Growth-Forecast-Multivariate-Time-Series-Analysis)
- Downloaded datasets from Organization for Economic Co-operation and Development (OECD)
- Applied Augmented Dickey-Fuller and KPSS tests for stationarity, and Johansen test for cointegration
- Checked correlation relationship with heatmap
- Fit the data into a VAR model, selected the lag order and forecasted the results
- Evaluated the time series using impulse response analysis and forecast error variance decomposition (FEVD) before inverting them back to their original form to plot the prediction trend
<img src="https://user-images.githubusercontent.com/36130927/128288132-f07c45d6-91d6-4480-851e-4464d8db349b.png" width=500>
