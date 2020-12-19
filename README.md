# Overview of Stock Analysis Project

The intent of this project is to assist our good friend Steve in performing a stock analysis on green energy stocks to help him make a recommendation to his parents on how to best diversify their portfolio. Steve's parents have invested all of their funds into DAQO New Energy Corp (Ticker: DQ), and Steve is needing our help to confirm if this is the best green energy stock to invest in.

Our goal of this analysis is to review the DAQO New Energy Corp and 11 other green energy stocks performance over the 2017 & 2018 calendar years, striving to provide the best information to Steve to make a recommendation to his parents if DAQO is the best company to invest in or if they should look into other green energy stocks.

# Overview of Stock Analysis Results

In performing the analysis of DAQO New Energy Corp and 11 other green energy stocks performance over the 2017 & 2018 calendar years, it is my recommendation to Steve that his parents should reconsider investing their full portfolio in DAQO based on the supporting evidence provided below.

## 2017 Green Energy Stock Analysis

In running our developed script against the 2017 data set, we can see that the DQ stock ticker earned an annual return of nearly 200% in our screenshot below. There were many stocks in the green energy sector that did well, as only 1 of the 12 stocks we reviewed produced a negative return - with many other stocks returning over 100% as well. 

![2017 Green Energy Stock Analysis](/Resources/2017_All_Green_Energy_Stock_Analysis.png "2017 Green Energy Stock Analysis")

While a 200% return is great to see on paper, there is some general concern over the total volume of shares that were traded of DQ over the year of 2017. With less than 36 million shares traded during the course of the year, this stock is by far the lowest stock traded (in terms of annual volume) in the sector with a daily trading volume of ~140,000 shares [36 millions shares divided by 251 trading days]. Stocks with a lower trading volume can be susceptible to larger spreads and more volatility.

## 2018 Green Energy Stock Analysis

After running our developed script against the 2018 data set, we can see that the DQ stock ticker had a major negative annual return of 62% in our screnshot below. Similar to the 2017 calendar year where nearly all green energy stocks had positive returns, in 2018 the larger green energy sector had a down year - with only 2 of the 12 stocks we reviewed that had a positive return. Unfortunately DQ was the worst performing stock in the sector, percentage wise, after producing the highest percentage return in 2017.

![2018 Green Energy Stock Analysis](/Resources/2018_All_Green_Energy_Stock_Analysis.png "2018 Green Energy Stock Analysis")

We did see a massive uptick in total volume of shares being traded of DQ in the 2018 year, as the stock effectively tripled their annual volume from 36 million shares in 2017 to 108 million shares in 2018. DQ was not the lowest volume stock this year, however they still were considerably lower than some of their peers in the sector. As we feared in our analysis from the 2017 analysis, DQ was susceptible to more volatility which may have led to their large negative return on the year. DQ started the 2018 year trading above $62 and ended the year at $23.40 - just $3.55 more than the stock was worth at the beginning of 2017! 

## Recommendation

It would be my recommendation to Steve and his parents to look to further diversify their portfolio in the green energy stock sector, rather than put their entire portfolio into the DQ stock. As seen above in the 2017 & 2018 images, the stock tickers for ENPH and RUN were the only two companies that had positive returns in both years. ENPH had two great years with returns of +130% in 2017 and +82% in 2018. RUN had a nominal return in 2017 of +6% and then followed that up with a +84% return in 2018, where most of the sector had negative returns that year. It was also great to see that YoY that both the ENPH and RUN annual trading volume increased - which shows that there is faith in these two companies and will likely be more secure companies to trade in over the long term.

# Summary

Below are the final summary questions and answers.

## What are the advantages or disadvantages of refactoring code?
- There are several advantages of refactoring the initial stock analysis code that we initially built. The first advantage of refactoring the code is the overall code cleanliness. The biggest advantage of refactoring the code, however, is of course the overall improved performance of the code. 

## How do these pros and cons apply to refactoring the original VBA script?
-  By moving away from nested loops, the pro of this code is that it is much easier to read for any other developer that would need to read the code or modify it. With this change in code cleanliness there is also the advantage of the original programmer less likely to make any identation/whitespace mistakes in their code solution. 

While this data set is rather small in nature and the initial code solution runs in under 1 second, another pro of the refactored code is that it runs nearly 4x faster, as seen in the images below. If this code solution was applied to a much larger data set that spanned thousands of rows, the initial code solution developed may take a substantial time to run. 

### Initial Stock Analysis Code Runtime

- **2017 Initial Stock Analsysis Code Runtime**

![2017 Initial Stock Analysis Code Runtime] (/Resources/Initial_Stock_Analysis_2017.png "2017 Initial Stock Analysis Code Runtime" )

- **2018 Initial Stock Analsysis Code Runtime**

![2018 Initial Stock Analysis Code Runtime] (/Resources/Initial_Stock_Analysis_2018.png "2018 Initial Stock Analysis Code Runtime" )

### Refactored Stock Analysis Code Runtime

- **2017 Refactored Stock Analsysis Code Runtime**

![2017 Refactored Stock Analysis Code Runtime] (/Resources/VBA_Challenge_2017.png "2017 Refactored Stock Analysis Code Runtime" )

- **2018 Refactored Stock Analsysis Code Runtime**

![2018 Refactored Stock Analysis Code Runtime] (/Resources/VBA_Challenge_2018.png "2018 Refactored Stock Analysis Code Runtime" )