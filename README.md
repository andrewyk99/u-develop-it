# U Develop It
U Develop It is a back-end application using MySQL to create a database consisting of a list of candidates that include their names, email, party ID, and the industry they are apart of. Using Insomnia to test the CRUD (create, read, update, and delete) operations to manipulate the data. This application makes use of tables to categories the candidates into one of three parties. There is also a voting system that is counted with an API route.

## Features
1. Users can request, create, delete, and update candidates.
2. Users can request and update parties, candidate's party, party information and affiliation, and delete a party altogether.
3. Users can request, create, and delete voters, as well as update a voter's email.
4. Users can cast a vote for a candidate.

## User Story
As a user, I want a database that holds a list of candidates and parties so that I can view all of them and how they associate with each other. I also want to see how many votes a candidate has as well as their industry association. I want to be able to manipulate the data so that I can change, update, and delete candidates, their associated parties, industries and votes.

## Installation and Usage
### Clone Repository
* git clone https://github.com/andrewyk99/u-develop-it.git

### Install Dependancies and Set Database
* Must have Sequelize
* Run `npm i`
* Then open MySQL by running `mysql -u root -p` and type in your password
* Then change database by running `USE election`
* Source the schema by running `source db/schema.sql`
* If you don't want to create the tables from scratch, can use seeds by running `source db/seeds.sql`

### Start Application
* Run `npm start`
* Use an API client such as 'Insomnia' and set localhost:3001

There is not a live website for this application.

## Tests
This application uses Jest to test the input. To run tests, after copying the code and installing dependencies, run `npm run test` in the terminal.