# cps404ex3
cps404 exercise 3: DOM Scripting

Exercise 3: DOM Scripting
Overview
In this assignment, you will complete a small browser-based adventure game.

Instructions
Warmup
Copy the adventure folder to your computer from the class files. Look at the source code for adventure.html. Then, open it in a browser. You should be able to navigate around the adventure world by entering commands like ‘n’, ‘e’, ‘s’, ‘w’.

Using your browser’s Developer Tools, set a breakpoint in the JavaScript and step through the code, examining values.

Part 1 (35 points)
Make the following enhancements without using any JavaScript libraries.

(15 points) Add code to the enterRoom( ) function to do the following:

Display the appropriate image
Display the exits
Display the items present in the room
Display the items carried by the user
The result should look like this:

Adventure

(10 points) Implement the take and drop functionality.

(10 points) Hyperlink the exits, so the user can click on them to navigate, instead of having to enter a command. Hyperlink the items carried and items present, so the user can click on them to take and drop items.

Part 2 (15 points)
Make a copy of Adventure.html named AventureJQ.html. Add a reference to the jQuery library hosted on a CDN. In this version, you will rework the code using JQuery as follows:

(5 points) Remove any explicit event handlers from the body of the HTML. Replace them with jQuery-style registrations done in the init() function. Don’t forget to register the init() function itself with the jQuery $( document ).ready( ) handler.

(5 points) Replace any uses of document.getElementById( ) with $( ) calls. When possible, invoke jQuery methods on the result, rather than directly manipulating the DOM object.

(5 points) Use the jQuery fade in / fade out functions to move from room to room.

Submission
Submit Adventure.html and AdventureJQ.html to the submission system.

Test your programs in Firefox, Chrome, and one other browser of your choice. Submit a report.pdf that specifies which browsers you tested with, gives 3 total screen shots showing your program running in at least 3 different browsers, and notes any issues. Tell how much time you spent on the exercise.

Include an Academic Integrity Report section:

Academic Integrity Report
By affixing my signature below, I certify that the accompanying work represents my own intellectual effort. Furthermore, I have received no outside help other than what is documented below and/or in program source code comments.

Signature

Date	Name/Email/URL	Nature of Help	Time Spent
 	 	 	 
