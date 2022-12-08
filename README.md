# Self-Assessment

## Overview of Project

This project served the purpose of communicating insights using tools like Tableau, after extracting, loading, and transferring visual datasets and databases. We used Python-based scripts to automate the clean up, restructuring, and rendering of the crime datasets. Our group analyzed crime statistics in the United States, posing the question: Is there a model that we can create to give warning and forecast higher crime cities and their respective neighborhoods. 

Our initial goals were mostly about generating a display model that can present the most optimal and least desirable locations, using crime counts as the determining variable. We also wanted to align court outcomes with our data for predictive analysis, but due to time and technology constraints with pulling census data and API's, we restricted our analysis to crime statistics. We connected the data to environmental or location variables instead of the demographic and cultural factors that play a role. Top Crimes Crimes by Year, Mont Crimes by Location (Latitude, Longitude) Crime by Area (Maps) Crimes by City by Year

## Results

We extracted and analyzed Kaggle crime datasets for simplicity reasons, as we sought to identify the most common crime types and the frequency of crimes across different localities. The cities we chose to look at were Los Angeles, Boston, and Baltimore, as they each have population densities that can offer variance. After cleaning and pulling data, our Boston set was the most limited, as there were an egregious amount of "null" values. We continued examining the variables in each set before merging the datasets. Once merged, we transformed the string objects into numerical identifiers from text to allow for us to create a model. We dropped nulls, columns, etc. while cleaning and restructuring dataset. For our model, we ran into an error trying to standardize data using the Scaler. 

## Self Assessment

This project served as a great learning opportunity as we got the opportunity to implement everything we've learned thus far. Initially, I was extremely overwhelmed at the thought of creating a database and extracting real data from it. Time management was my largest opportunity for the class in general, but specifically the project. I spent too much time trying to focus on the datasets being created and merged through pandas that it did not allow much room for adjustments once we hit a wall. We were also impeded by the need to save .csv files and datasets in a S3 bucket that I put together. This caused issues on 2 separate instances, as I was locked out of my account. Nonetheless, the issue was resolved and we continued on, though the RDS database was never able to connect to PostgreSQL. As a result, we adjusted from using Google Colab to narrow our tools and simplify processes.

## Team Assessment

The group got off to a pretty slow start as we struggled to identify specific questions we can examine the data with. Time management and attrition on the project were our biggest barriers. Melanie was extremely helpful along the way as I was tasked with creating and cleaning databases to build our dashboard from. As I struggled with technological issues, she was steadfast in offering assistance. Our largest opportunities for improvement include examining one dataset at a time to create more consistent and coherent data. Our database did not import into PostgreSQL and our dataset was not conducive for our machine learning model.
