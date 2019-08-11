## Interactive Recipe Website Website
Stream Three Project: Data Centric Development Milestone Project  - Code Institute

Access the  deployed website here: https://flask-automatic-deploys-fl.herokuapp.com
This website is a basic cooking recipe listing website using flask to connected to mongodb. It allows users to manipulate the database via the websites front end.
Users have the ability to add, delete and edit recipes as well as manging the categories these recipes are grouped under.


## UX
These are the user stories I came up with for the website:

- As a user I want to be able to see how reliable and secure the node is, to ensure the successful execution of my smart contract.
 
- As a user I want to be able to easily and quickly view recipes in order to make the dish myself

- As a user I want to be able to be able to add recipes so I can keep note of recipes I've created

- As a user I want to be able to edit a recipe so I can improve on existing recipes

- As a user I want to be able to delete recipes I do not like

- As a user I want to be able to see the resulting dish so that I have some idea if a dish looks appetizing

The primary goal of this website is create a large database of recipes to attract users and add adverts once enough traffic is generated.

## Features

A multi page website with 3 main pages
- Responsive layout and nav
- Home page which is automatically populated by Recipe entrys in the database
- Manage Categories page which allows users to add and delete categories
- Masthead with slider to inform users on website functionality

Modal Add Recipe Button
- an Add Recipe button which brings up a modal which allows users to add a recipe to the database without leaving the main listing page.
- image url option in add recipe form takes an image url and shows it to the recipe entries in the recipe listing


Recipe Editing and deletion
- Recipe entrys have button that allow deletion of entrys
- Edit recipe button brings user to a recipe editing page that autopopulates the form with the current information for editing.

 
### Features Left to Implement
- search functionality
- filter by categories functionality
- user Authentication so that users can only edit and delete their own entrys
- form validation so users can only enter valid recipe formats

## Technologies Used

- This project uses HTML and CSS programming languages.
 
- [JQuery](https://jquery.com)
    - The website uses **JQuery** as part of the Materialize  components.

- [AWSCloud9](https://aws.amazon.com/cloud9/)
    - This developer used **AWS Cloud9** for their IDE while building the website.

- [Materialize ](https://materializecss.com/)
    - The website uses **Materialize** frontend framework to simplify the structure of the website and make the website responsive easily.

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
    - The website uses a **MongoDB** database to store recipes

- [Flask](https://palletsprojects.com/p/flask/)
    - The websites uses the python microframework **Flask** and it's dependencies to autopopulate recipes lists and route templates for easy site updating.
  
- [Heroku](https://www.heroku.com)
  -The website uses the platform as a service (PaaS) **heroku** to automatically deploy the website
 
-[jonvadillo](https://codepen.io/jonvadillo/pen/PzYyEW)
  - Materialize snippet from user **jonvadillo** for nice card grid layout

## Testing
- I clicked all links and ensured they went to the right location, I tested the browser on Firefox & Brave(Chromium fork). 
- I tested the responsive layout using Braves inbuilt dev tools
- I tested various inputs into the database to ensure they were entered correctly

Issues yet to be resolved

- Add Recipe modal layout has too much white space depending on how long the recipe contents are
- Placeholder  image for when users submit invalid or no image for a recipe

## Deployment

This website was deployed using heroku and you can check it out [here](https://flask-automatic-deploys-fl.herokuapp.com/)

### Media

- Recipe entrys were taken from BBC Recipes website

### Acknowledgements

- I received inspiration for this project from Giulia and her amazing cooking
