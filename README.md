# Coursera_Capstone
 The Coursera Applied Data Science Capstone Project: The Battle of the Neighborhoods
 <br>by: _Diardano Raihan_
 <hr>

## Project Title: The Battle of the Neighborhoods - Starting a Coffee Shop Business
Build models for segmenting Toronto neighborhoods to find the best locations for starting a business

__Goal__: 
- To figure out the best locations for opening up a new coffee shop in Toronto City.

__Target Audience__: 
- Entrepeneurs, Business Owners, Stakeholders, Data Scientists

__Project Documentation__:
- [Project Blogpost](https://towardsdatascience.com/the-battle-of-neighborhoods-starting-a-coffee-shop-business-47dd32ad2ce6)
- [Project Report](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/document/Project_Report_The_Battle_of_Neighborhoods.pdf)

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
- Now, we will __explore__, __segment__, and __group neighborhoods__ into clusters to find similar neighborhoods in __Toronto City__. As far as this project is concerned, we will use the __Foursquare location dataset__ and use __Foursquare API__ to access it.

You can see the process in `Pre3_Clustering_Neigborhoods_Toronto.ipynb`

### 4. The Main Project Notebook

Objective: 
- Compile everything to acomplish the project's goal.

You can see the process in `Project_Notebook.ipynb`


Thank you,


Diardano Raihan
[LinkedIn Profile](https://www.linkedin.com/in/diardanoraihan)
