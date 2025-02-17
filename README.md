# Restaurant Pricing and Consumer Perception: DS4002 Data Divas Project 1
## Software and Platform section
We used Python to run the majority of our code either in Google Colab or in Rivanna. Platform varied by group member, so we used both Mac and Windows.In order to use Python in the most efficient manner, we used the following additional packages imported with this code: nltk, pandas, numpy, seaborn, matplotlib.pyplot, plotly.express, nltk.sentiment.vader, and scipy. 

![Sitemap Whiteboard in Green Purple Basic Style](https://github.com/user-attachments/assets/ed9e66e8-5d65-4750-89f4-aa084569b5c2)



## How to Reproduce Our Results
* **Step 1: Data Collection** <br>
To analyze restaurant reviews, we used the Yelp Open Dataset, containing information about many businesses, including user-generated ratings. We will store the cleaned dataset in csv format for further processing.
* **Step 2: Exploratory Data Analysis & Cleaning** <br>
The Yelp Dataset is an amalgamation of lots of customer reviews across all sorts of businesses from a wide variety of locations. Start by narrowing down the data to only include restaurants in the Philadelphia, PA area which have information about the restaurants’ price points and customer reviews. Then, clean the dataset. Handle missing values, remove any duplicates, and filter out non-restaurant establishments if any made it through your initial filtering. Generate summary statistics and create some visualizations of rating/price distributions to gain a deeper understanding of the preliminary dataset.
* **Step 3: VADER Sentiment Analysis** <br>
Once you have subsetted and cleaned the data, continue on to perform VADER Sentiment analysis on each resturant in the dataset to determine the average sentiment of their customer reviews. After that, average the restaurants' scores across the price groups (1-4) to compare average sentiment scores.
* **Step 4: Hypothesis Testing** <br>
After generating average sentiment scores for each price group, perform an ANOVA test to determine whether the mean scores are statistically different. A p-value of <0.05 will indicate that you can reject your null hypothesis (that each group has the same average sentiment). After ANOVA testing, continue on to perform Spearman Rank Correlation to measure the strength and direction of the correlation.
* **Step 5: Conclusions** <br>
Draw conclusions based on your data and statistical analysis.


