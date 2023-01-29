# Optional Assignment - Hiking Tracker

In this assignment you are going to create a website which can be used to record hiker's location. 

- Get the user's latitude and longitude without asking the user to enter it manually

- When the user presses the "Save" button then the user's latitude and longitude is sent to a Node service and then saved into the database. Start with storing it in an array instead of database.  

- The user can visit the website and see a list of all recorded locations 

- The user should be able to delete the recorded location

- The list of recorded locations should also allow the user to see the map. You can use this service: https://www.latlong.net/c/?lat=40.785091&long=-73.968285

- You can store a list of hiker's location in Redux state (Although in real apps I don't think it will be ideal to store such a long list in Redux) 

- Use Redux-Thunk to fetch list of locations inside actionCreators (HARD MODE)

**HARDMODE**

* Using the latitude and longitude find the name of the place that the coordinate represents and then store that name also in the database. You may have to find a service that takes in coordinates and returns the name of the place. 

