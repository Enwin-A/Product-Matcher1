 # Product-Matcher1
 So this is a personal project just to see if this is do able and has no intentions other than learning.
 Here this is a product matcher that reads one json file ie amazon data and then searches the name into another website here ulta and scrapes all the products with that search title and makes a json file it.
 It then further goes into each of those products and fetches the details of each and saves them.
 Next up what we do is we bring that up and compare both the data and gives it a good score based on the BERT Model from Transformers in python.
 Based on these scores the more closer the product name matches to the description and the name the higher the score and hence that would be the actual product matched.

 NOTE: there are issues with the reqests being sent which i have not fixed therefore you would mostly be blocked from the website after a while of scraping :)
