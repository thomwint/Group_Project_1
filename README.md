# Group_Project_1

Deployed Page: https://srandle93.github.io/Group_Project_1/index.html

This project was our first group project that allowed each of us to create a website of our choosing.  We, as a group, decided to create a quiz game using OpenTrivia API. The goal was to use Robohash API to create an avatar, have log in uthentication using Firebase, and display a quiz that counts your score per question. If you get it right, your score goes up, otherwise it goes down.

Each team member worked on different aspects, but my main focus was to implement the Firebase authentication and to help with the question and answer logic.

Group Project One
Describing our Technical Project
“Tell me about a technical project you’ve worked on”. [in two - three minutes]
Summary
Description: 
One or two sentences summarizing your project. This should be more interesting than technical.
Our application is using the Open Trivia Database API to generate and display trivia questions for a user to answer. The application opens to a login form that once completed, will save their login information to our Firebase Database and retrieve the information when a user returns. Our application is also using the Robohash API to generate a random avatar based on the email address of the user.

Motivation
Two or three sentences describing the problem the project solves.
Our application serves to ease boredom with random trivia questions of all categories and difficulties.  We designed our game, so that is has no time limit and can be played until it maxes out the number of API requests. 
Results
One or two sentences describing the end result

Our application is a trivia game with user generated questions across all categories and difficulty levels.  Each user is assigned a random robot avatar to their unique email address. There is no time limit.  
Team Efforts
Describe how you delegated work amongst your team members. 
Initially, the work was split up into front-end (html and css files) and back-end (javascript and firebase). Once the initial files were set up, we then all took turns contributing to each aspect of the application. When one person became stuck on a specific block of code, we would discuss the issue as a group, code in pairs, and then re-divy the current list of items to complete.

Individual Responsibilities
Describe what you contributed to the project as an individual—in other words, the parts of the project that you were accountable for.
Alex - I set up the initial html.index page with the layout we decided upon during the wire-framing phase. Then, once Symone had coded the initial app.js file, I jumped in to help get the question and answers to display.
Brittany - I did research and worked on email validation, getting the next question button to work, getting the score to display while playing the game, and general debugging. 
Thomas - I worked on the authentication of the login/signup form and the validation. I also backed up everyone to help with code that was not working (including answer validation, questions, etc) to make sure we did not fall behind.  I also got the next question button to work, the correct answer to show up green when clicked, incorrect answer to show up red when clicked, and fixed issues with debugging. 
Symone - I worked on the ajax calls for both APIs, and worked on Firebase before we gave up on it. I also made the Powerpoint. 
Yashar - I did CSS styling, and worked on Firebase writing the initial code we were going to use if we had decided to use the Firebase database for this application. 
Challenges
Describe any challenges you and/or your team encountered that you personally played an important role in resolving.

Using Firebase turned out to be quite a challenge.  We were able to get Firebase to store the email address, but struggled with adding a score that was continually updating.
Also, getting the next question to display with new answers proved to be a challenge as well.  
Email validation can be quite complicated. We learned that the only way to truly validate an email address is to send an email to a particular email address, which we decided was not necessary for this application.  


Improvements
Describe changes you would make going forward. These can be changes you’d make for better scalability; additional features you’d add; improvements you’d make to the codebase; etc.
Allow users to determine what kinds of trivia questions they answer (difficulty level, category).
Be more mindful of the API call limit - currently the application makes a new API call for each question, which, with multiple users could result in us reaching the limit
Associate User’s score with their username in Firebase Database so that when a user logs in, their previous score displays and they do not start at 0.
Adding a leaderboard that would display the top 5 highest scores with usernames, scores, and avatars. 
Adding a “Forgot Password?” button, which would send a reset password email to the  email address logged in Firebase, so the user would be able to access their account instead of making a new one. 

