# Capstone: Restaurant Reservation System

## Live site

URL: [https://reservation-frontend-react.herokuapp.com/dashboard](https://reservation-frontend-react.herokuapp.com/dashboard)

### Summary

I designed this application to benefit restaturants by allowing the staff to create reservations, edit reservations, 
seat reservations at tables, create tables, and search for previous reservations. 

## API

The restaurant reservation API was created using express and knex, and is found in the back-end folder. In order for the server to operate, make sure to 
add a .env file into the folder, the file should contain a database URL. 

### Endpoints

- [ ] GET - `Route: "/reservations", Result: JSON:{ data: reservations }`
- [ ] POST - `Route: "/reservations", Result: Status: 201,  JSON:{ data: reservation }`
- [ ] GET - `Route: "/reservations/:reservation_id", Result: JSON:{ data: reservation }`
- [ ] PUT - `Route: "/reservations/:reservation_id", Result: JSON:{ data: reservation }`
- [ ] PUT - `Route: "/reservations/:reservation_id/status", Result: JSON:{ data: reservation }`
- [ ] GET - `Route: "/tables", Result: JSON: { data: tables }`
- [ ] POST - `Route: "/tables" Result: Status: 201, JSON { data: table }`
- [ ] PUT - `Route: "/:table_id/seat", Result: Status: 200, JSON:{ data: reservation_id }`
- [ ] Delete - `Route: "/:table_id/seat", Result: JSON:{ data: table }`


## Technology Used

- [ ] React
	- [ ] React hooks
	- [ ] React router
- [ ] Express
- [ ] Node JS
- [ ] JavaScript
- [ ] Bootstrap CSS
- [ ] CSS
- [ ] HTML
- [ ] PostgreSQL
- [ ] RESTful API Architecture

## Installation

- [ ] Fork and clone this repository.
- [ ] Run `cp ./back-end/.env.sample ./back-end/.env`.
- [ ] Update the `./back-end/.env` file with the connection URL's to your ElephantSQL database instance.
- [ ] Run `cp ./front-end/.env.sample ./front-end/.env`.
- [ ] You should not need to make changes to the `./front-end/.env` file unless you want to connect to a backend at a location other than `http://localhost:5000`.
- [ ] Run `npm install` to install project dependencies.
- [ ] Run `npm run start:dev` to start your server in development mode.

### Screenshots

![Before Reservation Cancel](https://raw.githubusercontent.com/James-Sobeck/starter-restaurant-reservation/main/screenshots/us-01-cancel-before.png)
![Dashboard with Reservations and Tables](https://raw.githubusercontent.com/James-Sobeck/starter-restaurant-reservation/main/screenshots/us-04-dashboard-seat-button-before.png)
![Selecting table for reseravtion](https://raw.githubusercontent.com/James-Sobeck/starter-restaurant-reservation/main/screenshots/us-04-seat-reservation-submit-before.png)


