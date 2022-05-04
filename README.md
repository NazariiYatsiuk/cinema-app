# Cinema Application 
![528473_112968892189631_430605566_n](https://user-images.githubusercontent.com/94574503/166699244-d2470afb-350d-4c0d-a17d-1fe7c5c3d74f.png)
## Description
A simple Spring-based Web application, that allows find aviable sessions of a movie, add a ticket for a special movie session into shopping cart and to complete the order.
Supports registration of a new user and authentication
## Functions:
* Register a new user (**_POST_** `/register`);
* Authenticate (**_POST_** `/login`);
* Find a user by email (**_GET_** `/users/by-email`);
* Show a list of all cinema halls (**_GET_** `/cinema-halls`);
* Add a new cinema hall (**_POST_** `/cinema-halls`);
* Add a new movie (**_POST_** `/movies`);
* Show a list of all movies (**_GET_** `/movies`);
* Add a new movie session (**_POST_** `/movie-sessions`);
* Show a list of all aviable sessions of a movie by requested date (**_GET_** `/movies`);
* Update data of a movie session (**_PUT_** `/movie-sessions`);
* Delete a movie session (**_DELETE_** `/movie-sessions`);
* Put a ticket for a movie session into shopping cart (**_PUT_** `/shopping-carts/movie-sessions`);
* Show user's shopping cart contents (**_GET_** `/shopping-carts/by-user`);
* Complete user's order (**_POST_** `/orders/complete`);
* Show user's order history (**_GET_** `/orders`).
## Used technologies:
* Java 11;
* MySQL;
* Apache Maven;
* Apache Tomcat;
* Hibernate;
* Spring MVC;
* Spring Security;
## How to use:
1) Install MySQL DBMS.
2) Configure connection to your DB by filling actual JDBC driver, URL, username and password into `/src/main/resources/db.properties`.
3) Install and configure Apache Tomcat (**_version 9.x.x recommended_**).
4) Run Tomcat server and explore all features (you can log in as administrator (email: `admin@test.com`, password: `admin123`) or register a new user).
