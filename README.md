# CS6083-FinalProject
CSGY 6083 - Final Project - FatEar

README

Install these using Terminal:
npm install express
npm install cors  
npm install react-rating
npm install axios 
npm install react-router-dom 

The FatEar.sql was exported straight from my MySQL database, use it to import into a new database when testing out the code

Functions that work:
Registering a new user
Searching a song without being logged in
Searching a song from the database with song name, artist name (first or last), album name
Pulling the album art cover using an API from Last.fm
Rating a song from 1 to 5 stars
Average rating updating in live time
Reviewing a song
Review updating in live time on user's own profile
New review updating under the All Reviews tab on for other users after clicking refresh button on profile [Initially implemented it to update in live time but the amount of APT fetching that was being done was so quick in succession that it caused the site and other features to lag]

Functions that dont work:
Being able to access other user's profiles
Friend/Follow Requests

