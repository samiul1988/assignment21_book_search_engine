## Assignment 21: Book Search Engine
---
### Topic
MERN Stack with GraphQL

### User Story (Obtained from the assignment description)

```
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

### Acceptance Criteria (Obtained from the assignment description)

```
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button   
```

## My Actions and Notes

* The project was developed from a starter packege provided on the assignment description page.
* Basic considerations were as follows:
    * In this assignment, I've refactored the REST APIs to use GraphQL on the back end and added relevant functionality to the frontend  
    * I've removed the files/folders that were not relevant to the project anymore (e.g. backend controllers and routes folders)
    * Apollo server was implemented and applied as a middleware to Express server
    * Schemas were defined as instructed in the assignment
    * The existing authentication middleware was modified to work in the context of a GraphQL API
    * Apollo Provider was used so that the application can communicate with the Apollo Server
    * Application was deployed to Heroku

### Demo Run
![Demo Run](./assets/images/assignment21_demo.gif)

### Link of Deployed Application
[Heroku App Link](https://assignment21-book-search-engine.herokuapp.com/)
