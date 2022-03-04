# Time-Series-Modeling
MITx - MicroMasters Program on Statistics and Data Science - Data Analysis: Statistical Modeling and Computation in Applications - Fourth Project

The fourth project of the MIT MicroMasters Program course on Data Analysis focused on time series data where each observation corresponds to one point in time.  The objectives included carrying first some descriptive analysis with the help of visualizing the different components and their dependencies before moving towards modeling and eventually forecasting with the model. The three datasets include an environmental dataset that is said to be the most important data set in modern climate research, and two financial ones, which come from the MIT Billion Prices project (www.thebillionpricesproject.com).

The first dataset consists recordings of the concentration of carbon dioxide - CO2 - by Charles David Keeling at Mauna Loa, a volcano on the Hawaii island that he, and later his son, recorded since 1958 till now. What makes this data unique is that the samples have been taken for over a 60 year time span with the same measuring technique with very few interruptions and inhomogeneities. It is the longest continuous record of atmospheric carcon dioxide in the world and is an essential piece of evidence of the man-made increases in greenhouse gases that are believed to be the cause of global warming. 

The financial dataset contain the Consumer Price Index (CPI) which tracks inflation through a market basket of consumer goods and services and which is released monthly by the Bureau of Labor Statistics, the PriceStats daily consumer price index, and the Break-Even Rate (BER) which is the difference in yield between a fixed rate and inflation adjusted 10 year treasury note, and which can be seen as the market's view for the inflation rate for the next 10 years, on average.

The goal was to analyze each of the datasets and understand its variations before building a model to predict and analyze the results. Various different techniques and statistical methods were used to analyze and build the final models.

## Dataset

    - co2.csv: Provides a time series of the concentration of CO2 recorded at Mauna Loa for each month starting from March 1958.
    
    - PriceStats_CPI.csv: Contains the Consumer Price index (CPI) and PriceStats consumer price index starting from July 2008.
    
    - T10YIE.csv: Contains a time series of the BER starting from January 2003. 

## Access and Requirements

The file project4.ipynb is the Jupyter Notebook that contains all the code, visualizations and analysis of the project.

The dependencies and requirements can be seen from requirements.txt that can be installed in shell with the command:

      pip install -r requirements.txt
