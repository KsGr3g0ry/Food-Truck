### Created by Vivek Varadarajan and Gregory Brothers
*Created with Spring init containing JPA, Web, Flyaway, Postgres dependencies
*Added Cypress framework for testing.
*This is just for building the reps you need to be successful. Have fun with this and let's see what you can do!

### Setup
* Fork this repo to your GitHub account and pull it to your laptop.
* Build and run the codebase on your laptop.
* Run `docker run -d -p 5432:5432 --name my-postgres -e POSTGRES_PASSWORD=mysecretpassword postgres`(Change ports and password if needed)
* Change to /frontend and run `yarn install`
* Check application.yaml for container port.

# Food Truck Project
Foodies United, a large food truck vendor, needs to web application to show potential clients what they offer.

Your team is tasked with creating an application that displays all types of food, food description and prices.

# User stories
## Story: Add food names
### Narrative
```
As potential customer,  
I want to see a list of food name
```
### Acceptance Criteria
```
Given a food truck application with atleast one food item
When I go endpoint
Then I can see a list of food names 
```

# User stories
## Story: Add food description
### Narrative
```
As potential customer,  
I want to see a list of food description
```
### Acceptance Criteria
```
Given that one food item
When I go endpoint and hit a button/dropdown/icon
Then I can see a list of food descriptions by each name
```

# User stories
## Story: Add food prices
### Narrative
```
As potential customer,  
I want to see prices next to each food name
```
### Acceptance Criteria
```
Given that one food item
When I go to homepage
Then I can see a list of food names, description and prices
```