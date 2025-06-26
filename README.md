# Google Stock Price Prediction


Stock prices are highly volatile and influenced by various factors, making accurate prediction a major challenge in investment decisions. This project aims to predict Google stock prices using RNN, LSTM, GRU, and BiDirectional LSTM, comparing their performance using RMSE. The dataset includes Alphabet Inc. (GOOG) daily stock prices from 2013 to January 2024.   

Goals:  
- This project aims to predict Google stock prices using RNN, LSTM, GRU, and BiDirectional LSTM, comparing their performance using RMSE.

Insights:  
- It is known that Google's share price rose significantly from 2013 to 2021, then experienced a sharp decline in 2022 due to market volatility. However, in 2023-2024, the stock began to recover and showed an upward trend again.
- LSTM has the lowest accuracy, with the highest RMSE (6.28). The model is still able to capture stock price patterns, but lacks precision in following rapid price changes.
- GRU shows improved accuracy over LSTM (RMSE 4.33), with an advantage in computational efficiency as it has fewer parameters.
- Bidirectional LSTM provides the best results, with the lowest RMSE (4.07). This model is able to capture stock price patterns more accurately as it considers information from both time directions (past and future).

Conclusion:  
- Bidirectional LSTM is the best model in this project, as it has the lowest RMSE and is able to follow stock price patterns more accurately than LSTM and GRU. However, it also has higher complexity and requires longer training time.

If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on LinkedIn and Email : mfkriazh57@gmail.com and http://www.linkedin.com/in/muhammad-fakhri-azhar

#Python #DeepLearning #RNN #data-science
