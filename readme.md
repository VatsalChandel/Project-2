# Project 2
Project 2 consists of a simple and response login and sign up page with a backend. This backend allows users to create accounts and log in. This is done via a simple flask app and SQLAlchemy to store the username and passwords. 

When signing up, if a user enters an existing username, they are greeted with an error that tells them to use a different username. If the sign up is successful, they are taken to the login page where the can login. If they are unable to login, they are greeted with a message that tells them to double check their username and passwords to make sure they are correct. 