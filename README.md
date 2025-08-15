# Exploratory-Data-Analysis-EDA---Airbnub-dataset.
EDA project for Data Science and Data Analytics 

project overview

This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seabornfor cleaning, visualization, and analysis

Objective
- Analyze room types, prices, and availability across different neighborhoods.
- Detect potential outliers in prices
- Understand host behavior and listing patterns.

About Dataset the dataset 
-The dataset contains 20,765 entries and 22 features, including:

-id: Unique identifier for each listing
- name: Title of the Airbnb listing
- host_name: Name of the host
- neighborhood_group: Group (borough) where the listing is located
- latitude/longitude: Geolocation of listings
- price: Nightly rental price
- room_type: Type of accommodation (e.g., entire home, private room)
- reviews_per_month: Average monthly reviews for the listing
- availability_365: Number of available days in the year

Steps and Workflow

1. Importing Libraries and Data Loading
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - pip install pandas numpy matplotlib seaborn ( for installation of libraries)

  
2 . Data cleaning
   - Handling missing values by using stastical methods / drop the null values
   - Removing the Outlayers by using IQR Method
   - convert datatypes from one to another


3 . EDA (Exploratory Data Analysis)
1.Room type distribution:
 - Visualized the count of each room type using bar plots.
 - Identified Entire home/apt as the most common room type.
2. Neighborhood group insights:
- Analyzed price variations by boroughs.
- Manhattan had the highest average prices.
3 . Availability trends:
 - Used heatmaps to show correlations among price, availability_365, number_of_reviews, and beds.
4. Price distribution:
  - Used histograms to show the distribution of prices.
  - Majority of the listings were priced between $50 - $300.
5 . Host listings:
  - Analyzed hosts with multiple listings using boxplots to identify key contributors.
6. Review behavior:
  - Used pair plots to show relationships between number of reviews, price, and availability.

4 Data visulaization 
- Pairplot: To see correlations among price, availability, and number of reviews.
-  Heatmap: Showing correlations among numerical features.
-  Histograms and Boxplots: To detect outliers in price




