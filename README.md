# Pooling-System-Api
 This is a backend API for a polling system application. It is built using Node.js and MongoDB with the help of the Express framework.
# Features
1.Create a question (you can add as many questions as you want)
2.Add options to a question
3.Add a vote to an option of question
4.Delete a question → (Will not deleted if one of it’s options has votes)
5.Delete an option → (Will not be deleted if it has even one vote given to it)
6.View a question with it’s options and all the votes given to it
# Required 
/questions/create (To create a question)
/questions/:id/options/create (To add options to a specific question)
/questions/:id/delete (To delete a question)
/options/:id/delete (To delete an option)
/options/:id/add_vote (To increment the count of votes)
/questions/:id (To view a question and it’s options)
