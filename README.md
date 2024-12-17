# Craigslist Used Vehicles Dataset Analysis

## Project Description and Dataset Overview

Craigslist is the world’s largest collection of used vehicles for sale, but gathering all this information in one place can be difficult. This project leverages a scraper developed for a school project, which was later expanded to create a comprehensive dataset containing every used vehicle listing within the United States on Craigslist.

The dataset is scraped every few months and contains essential details about vehicle listings, such as price, condition, manufacturer, location, and more. The dataset includes over 18 categories of information, offering valuable insights into the used vehicle market.

You can access the dataset through the following link:  
[Kaggle - Craigslist Cars and Trucks Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data?authuser=1)

---

## Columns Description

- **ID**: Unique identifier for each listing
- **url**: Listing URL
- **region**: Craigslist region
- **region_url**: URL for the region
- **price**: Listing price of the vehicle
- **year**: Year of manufacture
- **manufacturer**: Vehicle manufacturer
- **model**: Vehicle model
- **condition**: Condition of the vehicle
- **cylinders**: Number of cylinders in the engine
- **fuel**: Type of fuel used (Gasoline, Diesel, Electric, etc.)
- **odometer**: Mileage (in miles)
- **title_status**: Status of the vehicle’s title
- **transmission**: Transmission type (Automatic/Manual)
- **VIN**: Vehicle Identification Number
- **drive**: Drive type (e.g., FWD, RWD, 4WD)
- **size**: Size category of the vehicle (e.g., compact, full-size)
- **type**: Generic type of vehicle (e.g., SUV, Sedan, Pickup)
- **paint_color**: Color of the vehicle’s paint
- **image_url**: URL for the vehicle image
- **description**: Description provided by the seller
- **county**: Erroneous column with irrelevant data
- **state**: State where the listing is posted
- **lat**: Latitude of the vehicle’s location
- **long**: Longitude of the vehicle’s location
- **posting_date**: Date the listing was posted

---

## Exploratory Data Analysis (EDA) Questions

1. **What are the top regions/states with the highest number of listings?**  
2. **How do car listing prices vary by manufacturing year?**  
3. **What is the distribution of car sales in different regions or states?**  
4. **How does the price vary across different car manufacturers?**  
5. **What is the relationship between vehicle condition and price?**  
6. **How do fuel types affect vehicle prices?**  
7. **What are the most common fuel types used in the listings?**  
8. **How do fuel types affect vehicle price, condition, or popularity?**  
9. **What are the most common manufacturers and models listed on Craigslist?**  
10. **What are the most common transmission types (manual vs automatic) in the dataset?**  
11. **How do vehicle prices vary between different transmission types?**  
12. **Is there a price difference between vehicles with different drive types (e.g., 4WD vs FWD)?**  
13. **What are the most common paint colors in the dataset?**  
14. **What are the most common vehicle sizes and types listed?**  
15. **How do vehicle sizes/types correlate with price and condition?**

---

## Conclusion

### Key Findings:

- **Top Regions/States**: The regions with the highest number of listings are dominated by Columbus, Jacksonville, and Spokane, with Columbus leading at 3,608 listings.
  
- **Price vs Manufacturing Year**: Car prices show variation based on manufacturing year, with notable spikes in certain years, especially 2021 due to inflation or increased demand for newer vehicles.

- **Price Variations by Manufacturer**: Luxury brands like Mercedes-Benz and Volvo have the highest average prices, while more economical brands like Saturn and Mercury show much lower prices.

- **Vehicle Condition & Price**: Vehicles in better condition generally have higher prices, with exceptions like the "fair" condition category, which may require further analysis for anomalies.

- **Fuel Types & Price**: Diesel vehicles tend to have the highest average prices, followed by gasoline-powered vehicles.

- **Most Common Manufacturers & Models**: Ford, Chevrolet, and Toyota are the most listed manufacturers, with the Ford F-150 topping the model list.

- **Transmission Types**: Automatic transmissions dominate the dataset, with manual transmissions being less common and generally priced higher.

- **Drive Types & Price**: Vehicles with 4WD have the highest average prices, likely due to their off-road capability.

---

## Technologies Used

- Python (for data cleaning and analysis)
- Pandas (for data manipulation)
- Matplotlib and Seaborn (for data visualization)
- Jupyter Notebooks (for analysis and exploration)

---

## Conclusion

This analysis provides valuable insights into the used vehicle market in the United States, helping to understand the distribution of vehicle listings and how various factors, such as condition, manufacturer, fuel type, and drive type, affect vehicle prices.

