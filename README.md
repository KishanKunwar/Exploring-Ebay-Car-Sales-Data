# Exploring-Ebay-Car-Sales-Data
This project will perform analysis on the dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website.

The dataset was originally scraped and uploaded to Kaggle. We've made a few modifications from the original dataset that was uploaded to Kaggle:

* We sampled 50,000 data points from the full dataset, to ensure your code runs quickly in our hosted environment
* We dirtied the dataset a bit to more closely resemble what you would expect from a scraped dataset (the version uploaded to Kaggle was cleaned to be easier to work with)

The aim of this project is to clean the data and analyze the included used car listings.

Some Of the Findigs are:

1. About two third of car in ebay has travelled abouT 150000 km and few of the vehicel are below 50000 km .
2. There is a large variety of ad created dates. Most fall within 1-2 months of the listing date, but a few are quite old, with the oldest at around 9 months.
3. Almost one fift of the car are of "volkswagen" brand where as just 29 of cars are from "lada" brand.
4. In terms of Brand analysis:
* Audi, BMW and Mercedes Benz are more expensive
* Ford and Opel are less expensive
* Volkswagen is in between

5. The price of a brand car does not depends mostly on the milage of that brand car i.e less the mean milage(odometer), less the price is not applied to this. There may be other condtions that made the price of the car less or more eg Year of Registration , unrepaired_damage etc
