= Web Technologies 2 - FA20 - Semester Project
== Developing a React Native Application for Semester Project
=== Each task below has equal weightage and code from all team members is required.

Distribution of the project is shown at the end of each task.

1. Clone this repository and after completion push your changes.
2. Landing Page Showing a list of items in database.
3. Use knowledge of Bootstrap and jQuery to enable. 
4. All records have a edit and delete option with them.
5. Records should comprise of students in the group (CMS_ID, Student_Name, Group_Name, Photo, Githublink) *Photos 40px x 40px can be **optional** and better to use public image URLs.*
6. Edit takes you to the page with all the record from database loaded in a form.
7. Insert new record using a separate form. 
8. Clicking on a record opens the single user record with a small bio along with the above mentioned details.


Names: Abdullah Mughal (208012)

Description: Bootstrap is used for designing. All records have an option to edit, view and delete. User will be able to add a student's record. The record contains Student name, CMS ID, email address, group members name and guthub url. Edit and add user takes a user to a new page. Clicking on the view button takes the user to a new page and that page shows complete details of a student. Because of shortage of time we were unable to implement firebase/mlab database. To store data, we are using JSON-server module which is storing data in a JSON file. 

Note: To run the code use command "npm run start:dev". We are using concurrently module to run JSON server and main server at a same time.
