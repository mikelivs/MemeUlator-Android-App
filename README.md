# MemeUlator-Android-App

androidapp-android-app-team05 created by GitHub Classroom

ITERATION 1: This first iteration focused on creating the app and setting up the 4 main page activities. We created "New Class", "Weight%", "Grades", and "Final Grade" buttons that bring the user to those specific activity pages. Furthermore, we implemented UserStory 1, UserStory 2 and User Story 12 into this "1st" iteration. We also designed three test files that test whether or not the button has been clicked to go to the next activity.(Espresso Test) We plan to implement and clean up the app and add more functionality in the next iteration.

USERSTORY1 As a user I want to add a “New class” to input the name of classes. Scenario 1: (Given-when-then) Given when the main menu is open, when the user clicks “new class” then page opens to input name of class.

USERSTORY2 As a user I want to add a “Weight %” to input various category weight%. Scenario 1: (Given-when-then) Given main menu is open, when user clicks “Weight %” then page opens to input weights of categories. Scenario 2: Given “New class” activity page is open, when user clicks “continue” then next page opens (Grades). Scenario 3: Given “grades” activity page is open, when user clicks “back” then “Weight %” page opens for input.

USERSTORY12 As a user I want to click the “back button” to go back to the previous screen Scenario 1: Given any page except the homepage, when I click the “back button”, I want to go back to the previous page.

ITERATION 2:

NEED TO ADD MORE USER STORIES BASED ON NEW APP FORMAT(SQL INTEGRATION...)

This iteration focused on integrating the various activities to work together. We add and implemented SQLite to our app to store/ save the information for the class in a database that the user enters their grades into. We also completely combined the weight and grades page into one activity to make the application more user friendly. Additionally, we made a few cosmetic changes to the app and implemented the ListView feature to the combined weight and grades page. Also a few user stories were added since our app changed a little.

USER STORY 5 As a user I want to input percentage for each category. Scenario 1: Given an empty percentage box, when I click on , then I will able to enter in a number. Scenario 2: Given a wrong percentage, when I click on the percentage box, then I will be able to change it.

USER STORY 6 As a user I want to go to the “Choose Category” page. Scenario 1: Given the Weights % page, when I click “continue”, then I will be brought to the “Choose Category” page. Scenario 2: Given the “Grade Input” page, when I click “back”, then I will be brought to the choose “Choose Category” page.

USER STORY 7 As a user I want to get to the “Grade Input” page. Scenario 1: Given the “Choose Category” page, when I click on one of the categories, it will bring me to a “Grade Input” page according to the category that I chose.

USER STORY 8 As a user I want to to input a name for the assignment. Scenario 1: Given the “hw grade input” page, when I click “the first blank button”, then I will be able to input a string name for the assignment.

USER STORY 9 As a user I want to input points earned for that assignment. Scenario 1: Given the “hw grade input” page, when I click “the second blank button”, then I will be able to input a double points earned for the assignment

USER STORY 10 As a user I want to input points possible for appropriate assignment. Scenario 1: Given the “hw grade input” page, when I click “the third blank button”, then I will be able to input a double points possible for the assignment

USER STORY 11 As a user I want to return to the home screen Scenario 1: Given any location within the application, when I click the “home button”, I will be able to immediately exit the application to the home screen. Scenario 2: Given the current state of the application, when I hit the “home button” i want the application to remember the task i was performing so I can go back and finish if need be.

USER STORY 13 As a user I want to see my final grade for the class Scenario 1: Given all grades are correctly submitted into the app, when I click the “CALC” button, i want to be taken to the final grades page Scenario 2: Given the “grade input” page, when I click the calculate button, I want to be taken to the final grade page. Scenario 3: Given the “grade input” page, when I click the calculate button, with no input, I want to be given a error message.

User Story 14 As a user, I want my input class data to be saved so I can come back to my input for convenience.

Scenario 1: When the user clicks "input new class", they should be able to type and add the name of their class.

Scenario 2: When the user clicks add, their class information will be saved to the database

Scenario 3: When the user advances to the main activity, they should be able to go back to the new class page.

User Story 15: As a user I want to use the Grade Input page

Scenario 1: when i click the Help button, I want a message to display on how to use the app.

Scenario 2: when i click the back button, I want to be taken back to the choose classes page

Scenario 3: when i click the blank next to the HW, Test, project or quiz label, I want to be able to enter in my grade and weight

Iteration 3: Final Iteration

Description: In the final iteration we were able to make the SQLite database functional. We obtained complete functionality of the delete and add buttons for the classes the user added. Also we implemented the finalGrade page to randomly generate a good, bad or neutral meme based on the user's final calculated grade. We

User Story 16: As a user I want to be able to click the calculate button to generate my final grade so a random meme will generate.

Scenario 1: When I click the calculate button, I want to be able to view my grade with a meme.

Scenario 2: Given the finalGrade page, when I click the back button I want to be able to go back to the input grade page to edit my grade input.'

Scenario 3: Given the finalGrade page, when I click the main menu button, I want to be taken back to the main new class page

User Story 17: As a user I want to be able to navigate the grade input and final grade page fluently.

Scenario 1: At the final grade page I want to be able to click the help button to have a message appear on how to use the page

Scenario 2: Given the final grade page,I want my first calculated grade to be saved so that i can go back to the main menu to choose a new class to calculate the grade for.

Scenario 3: Given the grade input page, I want to be able to save my input when I return advance forward and backward a page so that it'll be there when i return.

User Story 18: As a user I want a meme to correctly display the outcome of my grade, whether good, neutral or bad.

Scenario 1: On the final grade page, I want to be able to repeatedly click the calculate button to generate a meme based on the grade i got for the specific class I inputted data for.

Scenario 2: On the new class input page i want to be able to have multiple classes saved so that i can return back so view the grade calculated for that class.

Scenario 3: Given the calculate button, I want the memes to be different for each class i calculate my grades for.
