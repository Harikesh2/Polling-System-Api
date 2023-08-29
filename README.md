# Polling-System-Api
This is a backend API for a polling system application. It is built using Node.js and MongoDB with the help of the Express framework.

# Installation
Clone the repository using git clone https://github.com/Harikesh2/Polling-System-Api
Install dependencies using npm install
Start the server using npm start

# Features
Create a question (you can add as many questions as you want)
Add options to a question
Add a vote to an option of question
Delete a question → (Will not deleted if one of it’s options has votes)
Delete an option → (Will not be deleted if it has even one vote given to it)
View a question with it’s options and all the votes given to it

# Required Routes
/questions/create (To create a question)
/questions/:id/options/create (To add options to a specific question)
/questions/:id/delete (To delete a question)
/options/:id/delete (To delete an option)
/options/:id/add_vote (To increment the count of votes)
/questions/:id (To view a question and it’s options)

# Usage
Use Postman or a similar tool to make HTTP requests to the API endpoints listed above.

