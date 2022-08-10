![Bowman at the Shiver](https://github.com/manBow1119/PDGA-Predictor/blob/main/Bowman%20Shiver-1.jpg)

# PDGA-Predictor
This personal project will evaluate different machine learning models' ability to predict the winner PDGA Major tournaments, utilizing previous performance data scraped from the PDGA Website.

## Technologies Used
* Python (pandas, selenium, numpy, matplotlib)
* SQL (PGAdmin) 

## Approach to Data Collection 

### Scraping the Data
I used a basic approach to scraping the tournament data. Attempts to automate further proved difficult as Selenium had trouble locating certain elements after first attempt, limiting reproducibility. Although nested loops are utilized, there is very little data be scraped with each iteration, so it is likely not too greedy on computational resources. Ideally, however, this process could be run weekly after tournaments, and be used to predict the next Elite Series outcomes.

