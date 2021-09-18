# The Battle of the Neighborhoods: Starting a Coffee Shop Business
The Coursera Applied Data Science Capstone Project.
- __Author__: Diardano Raihan 
- __Email__: diardano@gmail.com
- __Social Media__: [LinkedIn](https://www.linkedin.com/in/diardanoraihan), [Medium](https://diardano.medium.com/)

## Project Summary

__Goal__: 
- To figure out the best locations for opening up a new coffee shop in Toronto City.

__Target Audience__: 
- Entrepeneurs, Business Owners, Stakeholders, Data Scientists

__Project Documentation__:
- [Project Blogpost](https://towardsdatascience.com/the-battle-of-neighborhoods-starting-a-coffee-shop-business-47dd32ad2ce6)
- [Project Report](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/document/Project_Report_The_Battle_of_Neighborhoods.pdf)

__Datasets__:
- [1st Data](https://tinyurl.com/vehicle-foot-traffic): The most updated record of traffic signal vehicle and pedestrian volumes in Toronto City. 
- [2nd Data](https://tinyurl.com/toronto-mci): The most updated record of crime incidents reported in Toronto City provided by Toronto Police Services.
- [3rd Data](https://tinyurl.com/toronto-postal-code): The list of Toronto neighborhoods represented by postal codes and their boroughs. 
- [4th Data](https://developer.foursquare.com/): The popular or most common venues of a given neighborhood in Toronto. 


The followings are the step by step process for working with the project:

### 1. Web Scraping: Toronto Postal Codes

We will start the project by scraping the following Wikipedia page.
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Objective:
- Obtain the data inside the html page containing a list of Toronto postal codes in the form of table and transform the data into a pandas dataframe!

You can see the process in [Pre1_Web_Scraping.ipynb](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/Pre1_Web_Scraping.ipynb)


### 2. Coordinate Retrieval: Toronto Postal Codes

Objective:
- Now, we will get the latitude and the longitude coordinates of each neighborhood in order to utilize the Foursquare location data later in the separate main project notebook.

You can see the process in [Pre2_Coordinate_Retrieval.ipynb](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/Pre2_Coordinate_Retrieval.ipynb)


### 3.  Segment & Cluster Toronto Neighborhoods

Objective:
- We will __explore__, __segment__, and __group neighborhoods__ into clusters to find similar neighborhoods in __Toronto City__. As far as this project is concerned, we will use the __Foursquare location dataset__ and use __Foursquare API__ to access it.

You can see the process in [Pre3_Clustering_Neigborhoods_Toronto.ipynb](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/Pre3_Clustering_Neigborhoods_Toronto.ipynb)

### 4. The Main Project Notebook

Objective: 
- Compile everything to acomplish the project's goal.

You can see the process in [Project_Notebook.ipynb](https://github.com/diardanoraihan/Coursera_Capstone/blob/main/Project_Notebook.ipynb)


Thank you,


Diardano Raihan <br>
[LinkedIn Profile](https://www.linkedin.com/in/diardanoraihan)
