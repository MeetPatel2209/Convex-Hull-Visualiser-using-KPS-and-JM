# Convex-Hull-Visualiser-using-KPS-and-JM


This is a complete Convex Hull Algorithm visualiser developed using NodeJS and C++ code for the Algorithm. The project was developed as a part of my Design and Analysis of Algorithm course at BITS Pilani, Hyderabad Campus. For running the Visualiser, follow the following steps : 

-> In the code folder, first download all the required node modules and dependencies. 
-> Run the app.js using nodeJS and it will start running on port 3000. 
-> In the visualiser, there are 3 ways to give input : 
   1) You can upload a CSV/Excel file containing the coordinates of the points for which convex hull need to be computed.
   2) You can also randomly generate points any number of points on the Algorithm visualiser and then run the alogrithm.
   3) You can also click on the canvas portion to generate a point and add it to the list of points for which we can to visualise the algorithm.

--> Some Limitations : 
   1) The number of points we can generate is infinity but it is limited by the canvas available for visualising. The coordinates maximum generated are 1140 * 780 pixels = 8,89,200 points.          But since the size of each point is 10 pixel by 10 pixel, comfortably we can visualise the algorithm for less than or equal to 8000 points.
   2) The feature of adding points on the canvas by clicking can only be used initially or when the webpage has been refreshed, otherwise the new points that are added by clicking on the            canvas will not be considered for visualisation.
 
