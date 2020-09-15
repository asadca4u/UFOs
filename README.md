# UFOs
### Overview of Project:
The purpose of this analysis is to use JavaScript to create a dynamic table that displays data from UFO sightings, while also allowing users to filter the data based on the date it was found, the city, state and country it was found in as well as the shape of the sighting. 

### Results:
##### Step 1: In order to use this webpage, scroll down to the table, with the filter input boxes to its left: 


![Image1](https://github.com/asadca4u/UFOs/blob/master/README%20Images/Image1.png)


##### Step 2: Next, click on one of the input fields and begin entering a filter criteria, making sure to follow the exact formatting, including case sensitivity:


![Image2](https://github.com/asadca4u/UFOs/blob/master/README%20Images/Image2.png)


##### Step 3: Click out of the input field and the table will automatically update the rows to display only those that match the filter criteria:


![Image3](https://github.com/asadca4u/UFOs/blob/master/README%20Images/Image3.png)


##### Note: Multiple filters may be used to update the table based on more specific criteria, and clearing a previously used input box will clear that filter perameter: 


![Image4](https://github.com/asadca4u/UFOs/blob/master/README%20Images/Image4.png)



### Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

##### Drawback of the Design:
Although this webpage is fairly intutitve to use, the major drawback of this dynamic table is the requirement for exact matches of the data in the table to be used when filtering using the fields to the left. While this may not be an issue with a smaller dataset that only looks into the United States and Canada, when larger datasets with global data entries are used, the filtering mechanism will run into issues. For example, writing "US" with capital letters in the country filter returns nothing in the table, however writing "us" with lower case letters will allow the table to function as intended. 

##### Recomendations for further Development:
1. The table should be hosted on a separate tab of the website in order to reduce clutter on the index page. 
2. The backend javascript code should be updated to allow for a more robust recognition of potential inputs into the filter input fields, including different abbreviations of states and countries, as well as different datetime formats, in order to avoid confusing users. 
