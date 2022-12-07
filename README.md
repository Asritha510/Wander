# Wander
Responsive Travel Website
Travel website to wander around the globe.
Used HTML, CSS, JavaScript, Node.js and Express.js to build the dynamic website, google.firebase - for storing the signup credentials.
Contains details of the places you want to wander, blogs and featured desinations.
Demo Link: https://youtu.be/V0VIjH3Js8o

# Database Linking
Go to console.firebase.google.com and create a project. 
You will be redirected to Project Overview Page, from the build drop down, select Firestore Database and click on create Database.
For security reasons, start in Test mode and select nam5 in location.
Create a collection and initialise the database structure.
Go to project settings and service accounts tab, select Node.js SDK configuration and click on generate new private key.
This will download the API key to access your database, so do not share it with others.
Rename the file as serviceAccountKey.json and place it in the root of your project directory.


# Generating API key
Go to Rapid API and search for TrueWay Places API, subscribe the API in the pricing to get the API key.
