Project Objectives
The Fine Dine project aims to:

Comprehensive Data Analysis: Perform extensive analysis of restaurant data, covering various metrics such as cuisines, ratings, costs, and locations.
Enhanced Decision-Making: Provide users with actionable insights to help them make informed dining decisions based on their preferences and budget.
User-Friendly Experience: Create an intuitive and interactive platform using Streamlit for effortless exploration of restaurant data.
Identifying Trends: Uncover dining trends and patterns across different cities and nationwide, highlighting popular cuisines, cost-effective dining options, and high-rated localities.
Culinary Exploration: Assist users in discovering new and diverse culinary experiences by providing detailed information on various cuisines and their popularity.
Data Collection
The data for this project was collected from the Zomato website using advanced web scraping techniques. The tools and technologies used include:

Selenium: For automated browsing and interaction with the Zomato website.
BeautifulSoup: For parsing HTML content and extracting relevant data.
The scraped data includes restaurant names, locations, cuisines, ratings, and costs.

Features
The Fine Dine app provides a variety of features, categorized into City-Wise Analysis and Total India Analysis:

City-Wise Analysis
Explore All Cuisines: Browse a wide range of cuisines available in a selected city without any specific preferences.
Search for Specific Cuisine: Find and analyze a particular cuisine by typing its name.
Cuisine Analyzer: Utilize multiple filters to explore different aspects of cuisines, such as popularity, best low-cost options, and worst expensive choices.
Locality Analyzer: Discover top-rated localities in a city based on average restaurant ratings.
Cost Vs Ratings: Understand how dining ratings vary with different price categories, aiding in making informed decisions based on budget and preferences.
Total India Analysis
Top Restaurants in India: Find the highest-rated restaurants across India based on user ratings and reviews.
Popular Cuisines in India: Discover the most popular cuisines available throughout the country.
Search for Specific Cuisine: Search and analyze any specific cuisine by entering its name.
Cuisine Filter by Ratings & Costs: Use various filters to examine different aspects of cuisines, such as popularity, best low-cost options, and worst expensive choices on a national level.
Cost Vs Ratings: Observe how restaurant ratings vary across different price categories to make better dining choices.
Popular Cuisine Combinations: Discover popular combinations of cuisines frequently paired together in restaurants.
Technologies Used
The Fine Dine project was developed using the following technologies:

Python: The primary programming language used for data scraping, analysis, and app development.
Selenium: For web scraping and automated browsing.
BeautifulSoup: For parsing HTML and extracting data.
Pandas: For data manipulation and analysis.
Streamlit: For creating an interactive web application.
Installation
To run the Fine Dine app locally, follow these simple steps:

Clone the repository:

git clone https://github.com/navinds/Zomato-Data-Analysis-and-Visualization.git
cd Zomato-Data-Analysis-and-Visualization
Install the required packages:

pip install -r requirements.txt
Run the Streamlit app:

streamlit run main.py
This will start the app locally, and you can access it in your web browser.
