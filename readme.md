I have used mongo db atlas as cloud database.
I have used beautifulsoup4 and requests to scrape the data.

I have scraped the data of [top restaurants in Mumbai](https://www.zomato.com/mumbai/top-restaurants):
- Restaurant details (name, description, address, geotag, cuisines, timings etc).
- Dishes in the restaurant(name, description, price, offer, discount, tags etc).
- All reviews of the restaurant (text, reviewer, # of likes and comments etc).
    
I have worked on Restaurant details and Dishes tables:
- Data sanity checks, cleaning.
- Deriving simple insights.
- Using nltk to derive insights from name, description, tags etc.
 
 
I have divided the code in three notebooks:
- Final_data_scraping_and_saving_to_mongodb_collection.ipynb 
 - It contains all the code used to scrape the code from Zomato restaurant site
 - and save the data to mongodb.
- Data analysis.ipynb
 - It contains data sanity checking, cleaning, creating new columns, analysis and all the plots.
- Rough work for xomato.ipynb - It contains the experimentation code.


I have not used Tableau/PowerBI before and I didn't want to learn it from scratch as it would itself take a weekend at least. So I have shown the plots in the notebooks only, using Matplotlib.

This assignment was my first experience with web scraping to collect big data. I have done a couple of web scraping projects before.

I have really found this project very interesting. I think I will work more on it to make it a complete portfolio level project. Especially the review data analysis.
