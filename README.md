# Coursera_Capstone
 The Coursera Applied Data Science Capstone Project: The Battle of the Neighborhoods
 <br>by: _Diardano Raihan_
 <hr>

## Case Study: The Battle of the Neighborhoods - Starting a Coffee Shop Business
Build models for segmenting Toronto neighborhoods to find the best locations for starting a business
- Project Blogpost: 
- Project Report:

The followings are the step by step process for working with the project:

### 1. Web Scraping: Toronto Postal Codes

We will start the project by scraping the following Wikipedia page.
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Objective:
- Obtain the data inside the html page containing a list of Toronto postal codes in the form of table and transform the data into a pandas dataframe!

You can see the process in `Pre1_Web_Scraping.ipynb`


### 2. Coordinate Retrieval: Toronto Postal Codes

Objective:
- Now, we will get the latitude and the longitude coordinates of each neighborhood in order to utilize the Foursquare location data later in the separate main project notebook.

You can see the process in `Pre2_Coordinate_Retrieval.ipynb`


### 3.  Segment & Cluster Toronto Neighborhoods

Objective:
- Now, we will __explore__, __segment__, and __group neighborhoods__ into clusters to find similar neighborhoods in __Toronto City__.

You can see the process in `Pre3_Clustering_Neigborhoods_Toronto.ipynb`
