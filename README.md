## 60hoursProject

Project splits in 2 (3) parts:

# overarching idea/outcome
- 6 page report
- how is stock/social media sentiment corralated, if it is? (delay, percentage of neg/pos sentiment on stock rise/fall)
- take a big(ish) set of stocks and use sentiment analysis to decide where to invest when and when to take money back out

# Time Series analysis/prediction (done by Ed & Beate)
- which data source/API to use
- which data to use (Close price, differences...)
- use different ML methods on data (1-5 stocks in the beginning, predicting 1-10 days in the future)
- ensemble methods/Monte Carlo for the different ML methods
- analyse different pre processing strategies (detrending, DC offset)
- analyse Signal Processing methods (Monte Carlo, Kalman filtering) on the data  
desired outcome:  
mean squared error comparison of different methods  
why did one method work for data set x?! --> analysis/interpretation

# Social data crawling (done by Alistair & Sumesh)
- find/get module that does "the job" (what do we need it to do? what works?)
- metric for usage of data (e.g. only one tweet that's negative  about x in that day shouldn't make a big influence)  
desired outcome:
- in which stocks to invest, when  

