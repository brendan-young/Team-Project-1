# Team-Project-1

### Group Collaborators:
- [Brendan](https://github.com/brendan-young)
- [Yinmu](https://github.com/ymcodespace)
- [Gareth](https://github.com/gleekl)

## Task Brief

* **Build a full-stack application**
* **Use an Express API**
* **Implement thoughtful user stories**
* **Be deployed online via Heroku**

## Technologies Used

* JavaScript
* HTML
* CSS
* Node.js
* Express
* MongoDB
* React
* Material UI (MUI)
* Bcrypt
* GitHub
* Heroku

## App Design
App design was collaboritively created and iterated via Adobe XD. A large area of discussion for the team was the user click through journey for the progression of their trips and the association with the users events that are aligned to each trip. 

![wireframing](https://res.cloudinary.com/dtfpk4gbd/image/upload/v1659665485/Team%20Project%201%20GA/Screen_Shot_2022-08-05_at_12.09.04_pm_f8w3je.png)

Front end design was achieved using Material UI framework for styling. 



## Challenges
### Relational Databasing
The team spent quite a bit of time discussing and planning our data structure. We chose to use relational databasing between trips and a one-to-many relationships to events withing the relevant trip. We discussed several other options including a relationship between country of trip and events within each country - but due to time constraints we chose to allow the user to create a trip with events from any part of that trip. This allows the user to allocate events accross a trip that includes multiple countries and continents.

However, relational databasing proved to have its own complexity when creating CRUD functionality for events that are nested within a trip. Understanding where the useState lies in order to create/update/delete events was a challenge that was overcome by  refactoring the code to ensure that when an event was changed, it was updated in the trip state, rather than having a separate state for trip. 


### Styling Challenges
In terms of styling challenges, to avoid refactoring of code it is best to incorporate the particular framework that is being used/to be used while building out functionality. This would avoid a lot of refactoring for front end formatting further down the track. 

