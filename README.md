# **Analysis of UFO Sighting with JavaScript**

## **Overview of Project**

This analysis aims to examine the data visualization on the webpage of UFO sighting through using the search criteria. Users will insert the criteria sorted by "Date", "City", "State", "Country", and "Shape" to manipulate the data of UFO that they want to access. This report will display two scenarios that a user might play with the webpage to show how the filter search work. In addition, this report will point out one drawback of this filter search webpage, as well as two possible recommendations for further development.

## **Results**

### ***Search scenario I: filter by single criteria***

The user wanted to sort the data of the UFOs by single criteria--shape. The user entered the "fireball" into the "Enter Shape" input area, then the records that have "fireball" shapes showed up, as in the image shown below.
![This is an image](https://github.com/ruimin1231/UFOs/blob/main/filter_search_by_shape.png)


### ***Search senario II: filter by multiple criteria***

The user wanted to sort the data of the UFOs by multiple criteria--Date and Shape. The user entered the "1/4/2010" and the "light" into the "Enter Date" and "Enter Shape" input areas, then the records that on January 4th, 2010 with "light" shape showed up, as the image is shown below.
![This is an image](https://github.com/ruimin1231/UFOs/blob/main/filte_search_by_shape_and_date.png)



## **Summary**

### ***Drawback***

The filter search successfully visualizes and sorts the data based on the five criteria of the "Filter Search" function. However, these are still some points that need to be reconsidered and improved. For example, there are no searching keywords for users to reference when they enter something to filter the data table. If they are not familiar with the table of the UFOs, and randomly type some words, they might find anything. 


### ***Recommendations**

1. Refresh button
When it comes to the refresh function, the "UFO Sightings" nested as the Navigation bar is far away from the Filter Search area. It's not easy for the user to click it when they want to refresh the data table. It will be easier for users If there is a refresh button next to the Filter Search area.

2. Search key words
It's hard for a user to choose one of the shapes of the UFOs that they're interested in when they access to the data at their first time. Understanding the whole list of shapes at the first place will be better for the users to make the next decision. For example, we can display the keys words as index next the "Enter Shape" as reference, such as "light","fireball","changing", "disk",etc., then the user could enter the key word or click the key word that they are looking for. 

