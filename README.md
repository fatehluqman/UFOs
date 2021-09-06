# UFOs

## Overview
We have created a webpage and dynamic table to search a database of UFO sightings with just a basic Date filter.
We are now adding additional functionality to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. 
In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Results
Initial step was to remove the update button and add the additional filter list items for city, state, country, and shape to the index.html file. 
To the app.js file a update filters and filter table functions were added. The function are used to read the user input in the filters and sort the table according to the filters. 
Lastly the update button has been removed in place of updating the web page when a change to filters is detected. 

The following demonstrates how the filters works. The initial table is displaced below with no filters applied.  The filters will have placeholder values which will help the user enter proper format for the filters:
![intial table](https://user-images.githubusercontent.com/62673123/132254103-97c13f68-e094-4b13-9a43-f6bbad690758.PNG)
The Date is now updated to 1/2/2010, once the date is entered and either "enter" or anther event is detected such as clicking outside the date input, the table will update:
![date_filter](https://user-images.githubusercontent.com/62673123/132254115-45825a43-110f-4128-8261-b71be2897f75.PNG)
Another example showing how the state filter works:
![state_filter](https://user-images.githubusercontent.com/62673123/132254170-70ed7e9e-270f-4389-b098-5fd631d08426.PNG)
And using multiple filters in this case date and shape:
![date_shape_filter](https://user-images.githubusercontent.com/62673123/132254153-24cc3ccc-9bc0-4892-b7d2-63373cabe2af.PNG)


## Summary
The additional enhancements are beneficial for a deeper dive into the UFO sightings database, however there are limitation to the current filters.  
One of the drawbacks would be if the date format or text inputs do not exactly match the data in the database, the table will not return any results.
Two possible enhancements that would help correct this issue would be:
1. To make the filters drop downs that consist of the values for each filter from the database, allowing the user to choose the item form the filter. 
this would account for formatting or spelling errors from the user and only allow the user to choose values already present in the database.
2. Instead of requiring the filters to match the database values, in case of spelling or formatting errors from the user, allow the filters a close match to values without being exact.
