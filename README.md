![logo](https://github.com/ttong94/DispatchSF/blob/main/src/ui/src/assets/images/logo_propeller.svg)

DispatchSF is a Dispatch San Francisco is a full-stack practical project to develop a parcel service website using robot and drone for the residents in San Francisco. This project was designed to have a multi-page interactive website for users to register, login, fill package information, select delivery route, mail and track their packages in real time in San Francisco.
Used MVP (Minimum Viable Product) and Agile Development Pattern to manage our project with 11 team members and participated in workflow design of the project.

Back End：
* Created MySQL database with eight tables on Amazon RDS and designed ERD (Entity Relationship Diagram) for the database.
* Used Spring MVC framework (Dependency Injection, Inversion of Control) to recieve requests from and send JSON object responses to the front end (Controller) and connect to database (Dao).
* Utilized Hibernate ORM (Object Relational Mapping) to provide mapping from Java entity classes to database tables.
* Developed a java algorithm to decode Google map polyline into a list of points of a route. 
* Used Google Places API to realize address validation.


Front end:
* Designed and developed a user interactive dashboard using ReactJS with Antd components.
* Created a multi-page user ordering web flow to let users fill package information and select the delivery option from a list of available options.
* Constructed 3 layers of React components to realize data communication (can be improved through Redux to reduce the complexity).
* Created a global ”step” variable to handle UI flow.
* Used Google Directions  API to show delivery routes and current location of user's package on the map.
* Utilized Axios to send requests and receive responses from back end.

Google API:
* Rendered different delivery routes with Google Directions API
* Used DirectionsService in Google Maps API to calculate robot’s routes between two points.
* Used DirectionsRenderer to display the robot routes.
* Used Polyline to display drone’s routes

