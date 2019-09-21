# Hourtel Front-end

This is a front-end side of my personal project Hourtel: a booking engine system.


## Technical

I written this part in React, using Redux to implement communication between component.


## Search by map

The hotels search is implemented with Google Maps API: 

* Dragging the map I get coods of the angles
* Those coords are passed to the back-end, and the to a SQL query
* Mysql creates a shape from this coords
* I get all the hotels which their coords are inside this shape area 
