# localserver

To run local server on your device, clone this repository.

1) make sure you install node modules using
``npm install``

2) If you'd like to launch the local server please run
``node server.js``

This should enable you to use ``localhost:3000`` with any API endpoints that 
are going to be setup in this repository using express

To check out the API endpoints and how they work please download Postman. 

**NOTE FOR THE CURRENT BRANCH YOU'RE SEEING:**
Please make sure that you setup firebase functions on your own.
Just follow the video, because if you tried to use this project, 
you won't be able to connect this project to your firebase account. 
This branch is just setup for you to see approximately what kind of changes are going to happen 
if you follow the videos. 
Also, this branch does not contain node_modules inside the functions directory.
It should be installed if you follow the video correctly, if not from the root of your project
navigate to functions and install the dependencies
``cd functions && npm install``
