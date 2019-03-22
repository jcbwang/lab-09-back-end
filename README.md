# City Explorer Back End
back end for city explorer app

**Author**: Jagdeep Singh

**Version**: 1.0.0 (increment the patch/fix version number if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for this class. (i.e. What's your problem domain?) -->
This site is being built so that we can get hands on experience with backend systems and produce a product that pulls from multiple databases and updates the information pulled regularly.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
Location-route
step 1: Copy base code from our Repo. `git clone https://github.com/jcwang118/lab-09-back-end.git`, then cd into directory `cd lab-09-back-end`.
step 2: In terminal window `npm install dotenv express pg cors superagent` and 
step 3: Create `.env` file containing environment variables: 
```
PORT=3000
DATABASE_URL=postres://localhost:5432/city_explorer
DARK_SKY_API_KEY=
YELP_API_KEY=
GOOGLE_MAPS_API_KEY=
MOVIE_DB_API_KEY=
MEETUP_API_KEY=
HIKING_API_KEY=
```
step 4: Create a `city_explorer` database, then create tables:
`psql -f data/schema.sql -d city_explorer`.
step 5: Run `nodemon`.
step 6: deploy if desired.




## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
Langauges currently in use include, JavaScript, node, JSON, npm.
NPM packages in use: express, cors, dotenv, superagent



## Change Log

2019-03-19 12:20 - Application now has a fully-functional express server, with a GET route for the /location resource.
2019-03-20 12:20 - Application has a /weather GET route and a /meetups GET route, and an error handler.


## Credits and Collaborations

Collaborators: Trey Herndon, Jesse Van Volkinburg, Bonnie Wang

Credit should be given to CodeFellows for providing all of the frontend javascript, html, and CSS. CodeFellows also gave guidance on the creation of the backend portion.




## DAY 1

Number and name of feature: Locations

Estimate of time needed to complete: 1 hour

Start time: 9am

Finish time: 10am

Actual time needed to complete: 1 hour


Number and name of feature: Weather

Estimate of time needed to complete: 1 hour

Start time: 10am

Finish time: 11:15am

Actual time needed to complete: 1:15 minutes


Number and name of feature: Errors

Estimate of time needed to complete: 1 hour

Start time: 11:15am

Finish time: 12:20pm

Actual time needed to complete: 1:05 minutes

## DAY 2

Number and name of feature: 1, 2, and 3 Data, Weather and Locations

Estimate of time needed to complete: 1 hour

Start time: 9:15
Finish time: 10:20

Actual time: 1:05 hours


Number and name of feature: 4 Meetups

Estimate of time needed to complete: 1 hour

Start time: 10:35
Finish time: 12:20

Actual time: 1:45 hours

## DAY 3

Number and name of feature: 1, Database setup and table creation

Estimate of time needed to complete: 20 minutes

Start time: 09:10
Finish time: 09:35

Actual time: 25 minutes


Number and name of feature: 2, Refactor API calls to use SQL

Estimate of time needed to complete: 30 minutes

Start time: 09:50
Finish time: 11:20

Actual time: 01:30

## DAY 4
Number and name of feature: 1, Add movies API call

Estimate of time needed to complete: 30 minutes

Start time: 09:40
Finish time: 10:47

Actual time:  67 minutes (discussing api formatting and docs)


Number and name of feature: 2, Add Yelp

Estimate of time needed to complete: 1 hour

Start time: 11:35
Finish time: 11:20

Actual time:  1.40 hours (discussing api formatting and docs, heroku issues)

Number and name of feature: 2, 

Estimate of time needed to complete: 30 minutes

Start time: 09:40
Finish time: 11:20

Actual time:  1.40 hours (discussing api formatting and docs, heroku issues)




