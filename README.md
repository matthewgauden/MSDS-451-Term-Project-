# MSDS-451-Term-Project-

## Intro
This is the term project repository for MSDS 451 Financial Engineering. The term project asks us to create a hypothetical fund -- in this case, an ETF -- and provide a general prospectus into the fund's investment philosophy as well as providing academic research, and eventually adding code that will perform portfolio optimization/simulation for an imaginary investor. 

## Checkpoint A
Checkpoint A is the first step in building the fund. In the checkpoint pdf, you will find the general philosophy when it comes to my created ETF (name will be decided in the future). The report also contains relevant academic research that I found that is relevant to my firm and our goals. This repository will be updated as the course goes along, with Checkpoints B and C, as well as the final product being added when they are complete. 

## Checkpoint B
Here, we take the project further and try to implement our philosophy on actual historical data. Multiple experiments were performed. Namely, a quadratic program that found the optimal allocation and expected return for our buy-and-hold portfolio. The second, was a Monte Carlo simulation -- similar to what can be found in MSDS 451 Programming Assignment 2 -- that generated 700 random portfolios and identified the portfolios with a maximum Sharpe Ratio (most efficient) and minimum volatility (risk). The third experiment was backtesting using an RSI momentum strategy as the basis of the test. 

## AI Dislaimer
Checkpoint A:
ChatGPT was used to simply scour the web and find potential academic sources for my project. All sources produced by ChatGPT were reviewed and only the ones I deemed to be relevant and useful were read and used. 

Checkpoint B:
Google Gemini was used in the Colab environment to assist with the RSI backtesting. I had multiple issues using the Backtesting.py library given my data structure. There were multiple errors and difficulties when trying to perform the test. Gemini was able to help explain these errors and suggest changes so that I did not have to rewrite the code at the beginning of the notebook. 
