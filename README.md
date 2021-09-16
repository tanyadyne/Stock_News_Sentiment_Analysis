# Stock News Sentiment Analysis
To view the main project, please click [here](https://nbviewer.jupyter.org/github/tanyadyne/Stock_News_Sentiment_Analysis/blob/main/News_Sentiment_Analysis/Scraping_News.ipynb).

To view the neural network model, please click [here](https://nbviewer.jupyter.org/github/tanyadyne/Stock_News_Sentiment_Analysis/blob/main/News_Sentiment_Analysis/Natural_Language_Classification.ipynb).

## Situation
With the record number of new investors following the "COVID" crash of 2020, I was interested in examining the reliability of stock news headlines in conveying the general sentiment of any particular stock. (Note that I was not necessarily interested in using this information for any trading strategy, I was merely interested in the sentiment portrayed by mass media and financial news outlets). 

## Task
The first step of this project was to create a dataset of news headlines upon which I would eventually train my neural network model. For this I used beautiful soup to scrape headlines from the popular financial website (/stock screener) FINVIZ.com. I also implemented a feature that would save the scraped data to a .csv file and update it with new headlines (though I had to manually run the program each time to do so). The second part of the project involved the creation of the neural network model. I used a Kaggle dataset containing 4845 stock news headlines with preassigned sentiment values to train my model on. I then implemented NLP techniques (tokenising and sequencing) on the daset before proceeding with a simple neural network in keras. I use a "sequential" model with 4 layers. After training the model on the Kaggle dataset, I return to my scraped Finviz dataset and implement sentiment prediction. I then create three wordclouds to depict the words the model associates with positive, negative and neutral sentiment.

## Action



## Result
