# TheHomeDepot_Project
The Eco-friendly Product labeling system is a project aimed at enhancing The Home Depot's Eco Options program by providing personalized product recommendations based on user preferences for eco-friendly and sustainable products.

# Eco-friendly Product labeling System for The Home Depot

This repository contains datasets and code for a recommendation system built for The Home Depot. The system helps match customers to eco-friendly products based on their sustainability preferences.

## Datasets

The datasets used for this project are:

- **data.csv**: This is the original dataset containing product information.
  
- **cleaned_data.csv**: After rigorous data cleaning and processing, the refined version of `data.csv`.
  
- **cleaned_eco_products.csv**: An enhanced dataset that features additional sustainability attributes such as carbon footprints and more.

- **Final_data.csv**: It's the `cleaned_eco_products.csv` but with added sustainability labels. These labels include:
    - Recyclable
    - Water Efficient
    - Energy Efficient
    - Certified Eco-Friendly

- **User_data.csv**: Contains essential user information including:
    - User_ID
    - User_Name
    - Sustainability Preferences of the user
  
- **user_matrix.csv** & **product_matrix.csv**: These datasets emerged post matrix-factorization. They're essential for the recommendation system to function.

## Jupyter Notebook

- **Eco_THD.ipynb**: This Jupyter notebook is where all the magic happens. It covers:
    - Data Cleaning & Preprocessing
    - Creation of Sustainability Labels
    - Matrix Factorization
    - User-Based Recommendations
  
## Output

- **user_recommendations.csv**: This CSV contains the final recommendations made by the system. It associates every user with a set of products that align with their sustainability preferences.

## How to Use

1. Clone this repository to your local machine.
2. Install necessary Python libraries and dependencies.
3. Run the `Eco_THD.ipynb` notebook to understand the entire workflow or to replicate the recommendation process.
4. Examine `user_recommendations.csv` for the end results.

## Author

Anish Gaikwad

