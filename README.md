# Capstone project
I am researching the most common dog breeds in each of the 5 boroughs in New York. I am wanting to know if location or income has an effect on which type of dog breed that New Yorkers tend to go with.
# DogbreedNYC

Dogs are everywhere. There is a high probability that at some point in your life you have owned a dog, or know someone that has. So what type of dogs does the city that never sleep tend to want in their homes. I will break down the numbers and give a deeper look into each of the 5 boroughs. 

# Questions
What are the top five dog breeds in each of the five boroughs?
Does income effect the type of dog that New Yorkers tend to go with?
Which dog breeds are most popular in general in New York?

# Gathering data
The Data used for the project are from these sources.
1. [Licenses](https://www.kaggle.com/datasets/smithaachar/nyc-dog-licensing-clean)
2. [Boroughs](https://data.cityofnewyork.us/City-Government/Real-Property-Income-and-Expense-Form-non-complian/wvts-6tdf/data_preview)
3. [Income] - I scrapped the web and compiled my own list of median income based in each of the 5 boroughs.

# Project requirements

1. Load Data
I read in two CSV files and one geopandas/json file

2. Cleaning and joining data
I merge in Boroughs and Licenses using an inner join on boro_name. I also merge Licenses with Income. I then clean the data to show the only columns needed the rest of the way.

3. Visualize Data
I use a total of 10 matplotlib visualizations for this project. 

4. Best Practices
1. First you will want to create a venv: python -m venv venv 
        [note:] If you are on a Mac, use 'python3'
2. Activate your virtual environment: source venv/Scripts/activate
        [note:] If you are on a Mac, use source venv/bin/activate
3. Install the required packages: pip install -r requirements.txt

5. Interpretation of Data
I used markdowns to explain my graphs and comments to show what the code used does.

# Findings
![Yorkshire Terrier](yorkshireterrier_adult.jpg)
While the median income from Manhattan to the Bronx is more than double. My findings will clearly show that income does not play a significant in which dog breed people go with. The most common dog owned in each of the five boroughs is Yorkshire Terrier. For additional information, we also looked at the most common name, Bella, and the most common gender is male. 