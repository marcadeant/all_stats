# all_stats
 Python library for automated statisticals tests for all

# Installation 

 Firstable, you need a python 3.8's version or greater to run all dependancies correcly

**1. Dependancies installation** <br>
 Clone the latest version of the library with `git clone [url] -b latest` <br>
 Dependencies can be installed with the command line : `pip3 install -r requirements.txt` (python virtualenv is highly recommanded)  
 Move **correlation_test.py** into your python work directory (or python virtual environment directory)  
 
# Usage** <br>
Once the set up completed, import the correlation test module as a library in a Python script `import correlation_test as ct`  
Current version cover all automated statistical test as describing below :   
* Pearson Chi-2's test (Categorical correlation) and V Cramer (correlation force measurement)
* Spearman's test (quantitative correlation)
* Shapiro's test (Normality test)  <br>

Upcoming test : 
* Anova's test 
* Pearson's test (quantitative)
* Student test

**3. Example with Pearson Chi-2's test** 

