# Sunrise-Sunset-Lookup-Application
This application allowed users to enter latitude and longitude coordinates to retrieve sunrise and sunset times for a specified location. Key features included:
# Application Requirement:
•	The application should have an EditText for entering the latitude and longitude of a location where you want to look up when the sun will rise and when it will set. The user can then click on a “Lookup” button and the app will send a query to the server.
•	The URL for searching is “api.sunrisesunset.io/json?lat=XXXXX&lng=YYYYYY&timezone=UTC&date=today where XXX is the latitude of the location and YYY is the longitude of the location.
•	Your application should show the results from the server, and also have a button to save that location to the database.
•	There should be a button to view “favourite” locations from the database in a recycle view. If the user clicks on one of those locations, then the application should then do a new query for that location using today’s date to show current times for sunrise and sunset.
•	There should also be a button to delete that favourite location from the database.
•	The SharedPreferences should save the user’s search term so that the next time you start the application, the previous search term is shown in the search field.
# Knowledge Requirement:
1.	All activities must be integrated into a single working application, on a single device or emulator. You should use GitHub for merging your code by creating pull requests. The demo must occur from the main branch on your project’s repository.
2.	The entire project must have at least 1 activity written by each person in your group (so at least 1 activity per person). Your activity must be accessible through a graphical icon from a Toolbar.
3.	Each person’s project must have a RecyclerView somewhere to present items in a list. 
4.	Each person’s project must use a database to store items. The user must be able to add and delete items, which should be displayed somehow in a RecyclerView. It should work similarly to the chat room labs you did this semester.
5.	Each activity must use Volley to retrieve data from a server. You cannot use Executor or AsyncTask
6.	Each activity must have at least 1 Toast, 1 Snackbar, and 1 AlertDialog notification.
7.	Each activity must have at least 1 edit text with appropriate text input method and at least one button.
8.	Each activity must use SharedPreferences to save something about what was typed in the EditText for use the next time the application is launched.
9.	Each person’s project must have a help menu item that displays an AlertDialog with instructions for how to use the interface.
10.	There must be at least 1 other language supported by your part of the project. Google Translate can help you perform the translations.
11.	The interfaces must look professional, with GUI elements properly laid out and aligned. 
12.	The functions and variables you write must be properly documented using JavaDoc comments. Each file must include a header stating the purpose of the file, the author, the lab section, and the creation date.
13.	Each team member must add at least 5 test cases that test the interface on their part of the application.
