<<<<<<< HEAD
A web crawler to scrape data from New Delhi, Kolkata, Mumbai,
Hyderabad, Chennai, Bangalore, Mysore using a scrapy project.
How to run:
1. Install scrapy
2. Run "scrapy crawl -o stuff.json" on command line
3. Stuff.json will contain json data of scraped stuff. The spider code is in /spiders/zomatospider.py. Uncomment the other cities' URLs in the start_urls list.
4. Do json to csv conversion if required.
Note:
I have written code so that lat, lon, cities, reviews are scraped. We can scrape a lot more by modifying zomatospider.py.



## Data ( I don't know why this is not happening)
The scraped data can be found in `\data` and it contains three files `restaurants.csv`, `cuisines.csv`, `collections.csv`. Each restaurant in the dataset is uniquely identified by its `r_id`. `restaurants` contains the following variables:

- `r_type`: Whether the listing is a casual dining restaurant, a fine-dining restaurant, a cafe etc.
- `r_name`
- `area`
- `bookmarks`: # bookmarks of the restaurant made using the bookmark feature in the website
- `checkins`: Check-ins using the "been here" feature
- `city`
- `cost`: Cost for two in rupees
- `r_address`
- `link`
- `photos`: No. of photos of the restaurant uploaded to the service
- `r_id`
- `r_latitude`: Latitude coordinate of the restaurant's location
- `r_longitude`: Longitude coordinate of the restaurant's location
- `rating`: Average rating out of 5
- `rating_votes`: Number of ratings
- `reviews`: Number of reviews
=======
# MyWebScraper
>>>>>>> 9c384b9f6d41a60608175e9c6cf7bde2846a09b6
