
#  Questions that we want to ask:
# 1. How big should our dataset be to complete the analysis? <Br>
We went with a seven year daily closing of the S&P 500 stocks as our data set.  Our main concern was model performance if we went with a bigger data set, however, we wanted  to ensure we went back far enough to get enough data as we were aware the correlation of stock pairs can switch from positive to negative over time. In our first phase of the project, we didn't go beyond the S&P 500 data, but we do realize that the S&P 500 data shows some positive correlation pairs. Therefore, the model is meaningful. It will generate some insights for us with more data feed in our model.  <Br>


# 2. Do we limit it to just stocks? <Br>
The initial hope was to create a model to not only measure correlation amongst stocks, but indexes and potentially cryptos too.  In the end we determined it’s best to calculate only stock pairings to limit the scope for our first phase with the potential to add future datasets as part of a later phase. In the future phases, we will gradually add more datasets, such as Crude oil etc. to our model.  <Br>


# 3. Should we consider loosely correlated calculated values? <Br>
All pairings with a “r” value between -1 and 0 would be considered inverse correlated. A significant inverse correlated pairs will happen at -0.7 to -0.998.  



# 4. Should other variables be considered when calculating correlation other than closing price? <Br>
Even though a paring selection may posses a strong inverse correlation, we were aware this does not necessarily imply one has the casual influence on the other.  With this being said, we felt there was still value in calculating inverse correlation treating market conditions as a base case variable that applied to all stocks within the data sample. In the future phases, we do want to analyze the daily trading volumes and also want to analyze the outliners that appearing on our models. We believed those outlines could present as some firm or industry wide historical event, such as split stocks etc. <Br>

# Key Findings
Calculating inverse correlation via pythons “.corr” functionality based on average closing price produced accurate correlation results<br>
To limit the scope of this project’s dataset requirements, we went with the S&P index stocks from 2015 to 2022 as our dataset due to it’s diversity of large market cap equities. <br>
Upon completion, we found there were no strongly inversed correlated pairings within the S&P index.  This leads us to believe that to find strongly inverse correlated pairing within the stocks listed in the index, we would need to look outside of it.<br>
Creating data frames to store big volumes of financial data and looping thorough them is handled quite efficiently in python, producing results within minutes.<br>
