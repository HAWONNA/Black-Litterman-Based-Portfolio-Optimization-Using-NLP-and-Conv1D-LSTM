### Project Title: A Study on Black-Litterman-Based Portfolio Optimization Using NLP and Conv1D+LSTM

**abstract:**  
This project investigates portfolio optimization within the Black-Litterman framework, specifically employing natural language processing (NLP) and Conv1D+LSTM techniques to model market views. To evaluate the effectiveness of Black-Litterman-based portfolio optimization, the study conducts a comparative analysis using various weighting methods. These include: 1) Equal Weighting, 2) Markowitz Mean-Variance Optimization Weighting based on the Efficient Frontier and Maximum Sharpe Ratio, 3) Market-Cap Weighting, 4) Free-Float Weighting (Float-Adjusted Market Cap Weighting), 5) Weighting by Mean-Variance Optimization (MVO) with Implied Returns, and 6) Weighting by Implied Returns with Adjusted Views. 

Weighting methods (1) through (4) are applied without the Black-Litterman model, while methods (5) and (6) incorporate Black-Litterman to determine if significant differences in portfolio performance arise. The performance evaluation criteria include Average Return, Standard Deviation, Sharpe Ratio, Minimum Return, Maximum Return, Alpha, and Beta. Backtesting is conducted on a quarterly basis for each phase of the market from Q1 to Q4 of 2021, using market cycle data from Statistics Korea's Business Cycle Clock.

The portfolio consists of eight selected stocks: Samsung Electronics, SK Hynix, Samsung Biologics, LG Chem, Naver, Hyundai Motor, Samsung SDI, and Kakao. For the Black-Litterman model, NLP techniques are employed by scraping Naver news headlines and tokenizing words using the Konlpy library. Sentiment analysis is conducted to compute the ratio of positive to negative words, which is then used to define the P (Market View Matrix) and Q (Market View Returns) matrices.


**references:**
1. 조수지, 권홍규, 양철민. "기업 재무분석을 위한 한국어 감성사전 구축." *Korean J Financ Stud.*, 2021.
2. KIM, Sunwoong. "Robo-Advisor algorithm with intelligent view model." *Journal of Intelligence and Information Systems*, 2019.
3. S. Jain, R. Gupta, and A. A. Moghe. "Stock Price Prediction on Daily Stock Data using Deep Neural Networks." 2018.
4. L. S. Chong, K. M. Lim, and C. P. Lee. "Stock Market Prediction using Ensemble of Deep Neural Networks." 2020.
5. MIN, Liangyu, et al. "A black–litterman portfolio selection model with investor opinions generating from machine learning algorithms." *Engineering Letters*, 2021.
