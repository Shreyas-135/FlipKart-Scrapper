Flipkart Product Scraper
This project is a Python-based web scraper that extracts product details (price, ratings, and reviews) from Flipkart product pages and stores the scraped data in a MongoDB database.

Features
Scrapes product prices, ratings, and reviews from Flipkart.
Stores the scraped data in a MongoDB collection.
Can handle multiple product pages.
Utilizes Python libraries like requests, BeautifulSoup, and pymongo.
Requirements
Before running this project, ensure you have the following:

Python 3.x
MongoDB
Required Python libraries (requests, BeautifulSoup, pymongo)
You can install the necessary libraries using the following command:

bash
Copy code
pip install -r requirements.txt
How It Works
The scraper works by sending a GET request to Flipkart product pages, parsing the HTML content, and extracting the desired data. This data includes:

Product Price
Ratings
Customer Reviews
The extracted data is then saved into a MongoDB collection.

Installation and Setup
Clone the repository:

bash
Copy code
git clone https://github.com/Shreyas-135/flipkart-product-scraper.git
cd flipkart-product-scraper
Install dependencies:

bash
Copy code
pip install -r requirements.txt
MongoDB Setup:

Make sure you have MongoDB installed and running on your local machine or have access to a MongoDB Atlas cluster. Update the MongoDB connection string in the Python script (scraper.py) to point to your MongoDB instance.

Run the scraper:

bash
Copy code
python scraper.py
The scraped data will be stored in your MongoDB database.
