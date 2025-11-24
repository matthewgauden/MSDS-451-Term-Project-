# MSDS-451-Term-Project-

## Intro
This is the term project repository for MSDS 451 Financial Engineering. The term project asks us to create a hypothetical fund -- in this case, an ETF -- and provide a general prospectus into the fund's investment philosophy as well as providing academic research, and eventually adding code that will perform portfolio optimization/simulation for an imaginary investor. 

## Checkpoint A
Checkpoint A is the first step in building the fund. In the checkpoint pdf, you will find the general philosophy when it comes to my created ETF (name will be decided in the future). The report also contains relevant academic research that I found that is relevant to my firm and our goals. This repository will be updated as the course goes along, with Checkpoints B and C, as well as the final product being added when they are complete. 

## Checkpoint B
Here, we take the project further and try to implement our philosophy on actual historical data. Multiple experiments were performed. Namely, a quadratic program that found the optimal allocation and expected return for our buy-and-hold portfolio. The second, was a Monte Carlo simulation -- similar to what can be found in MSDS 451 Programming Assignment 2 -- that generated 700 random portfolios and identified the portfolios with a maximum Sharpe Ratio (most efficient) and minimum volatility (risk). The third experiment was backtesting using an RSI momentum strategy as the basis of the test. 

## Checkpoint C
Using both the previous two checkpoints and the programming assignments, we are building onto the work we've done so far to continue to refine and optimize our portfolio. In this checkpoint, an additional ETF fund was added (QQQ). Based on work in previous assignments it was seen that this asset could potentially boost the growth seen with our portfolio, albeit with more risk. There was a shift in philosophy for the fund. The fund is now willing to take on clients who accept higher volatility in their assets if it means excess returns on their initial investment. The experiments performed in this checkpoint were: Adding QQQ and comparing portfolio performance using the S&P 500 index as a benchmark, Monte Carlo simulations to gain a distribution for various metrics relevant to our fund, and finally introducing a base pay structure for fees and management for our clients. 

## Final Project
This is the Final Report and code for the project as a whole. In the code, fees were both implemented and optimized for the fund to manage daily operations. The Monte Carlo simulations were also performed on both portfolios (with fees and without). The code builds on previous checkpoints and assignments, as through each step in the pipeline the fund's strategy and methods have adjusted accordingly as new ideas have been discovered. As for the report, it provides a comprehensive look at the fund's general philosophy, the trading strategy implemented on the historical data, a performance evaluation based on both portfolio metrics and MC simulation distributions, and finally, a recommendation for starting the hypothetical firm along with references. 

## GenAI Tools Disclaimer
Checkpoint A:
ChatGPT was used to simply scour the web and find potential academic sources for my project. All sources produced by ChatGPT were reviewed and only the ones I deemed to be relevant and useful were read and used. 

Checkpoint B:
Google Gemini was used in the Colab environment to assist with the RSI backtesting. I had multiple issues using the Backtesting.py library given my data structure. There were multiple errors and difficulties when trying to perform the test. Gemini was able to help explain these errors and suggest changes so that I did not have to rewrite the code at the beginning of the notebook. 

Checkpoint C:
Google Gemini was used in the Colab environment to assist with visualizations, as well as to print repeat code cells used from my Programming Assignment 3 to be modified for the experiments performed. This made the notebook much more efficient to use. There was also an error resolved with Gemini involving the use of the S&P 500. The ticker (SPX) was incomplete and I got an overload error, but the Gemini feature was able to find the accurate (^GSPC) ticker label to retrieve the historical data from Yahoo! Finance. 

Final Project:
Google Gemini was used in the Colab environment to assist with visualizations. Gemini was also used to optimize the backtesting and trading strategy. In Checkpoint C, I was not satisfied with the results of the portfolio when it came to Alpha, Sharpe Ratio, and Max Drawdown. I used Gemini to give me a suggestion on how to adjust the minimum momentum threshold to both increase returns and the Sharpe Ratio for the portfolio. It also gave suggestions on fee structure, as the exact percentages were arbitrary and tinkered until I got the performance I was happy with compared to the SPX benchmark values, while keeping in mind not to over-increase Max Drawdown value. 
