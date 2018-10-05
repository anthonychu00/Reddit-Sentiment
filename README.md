# Reddit-Sentiment

Web App that takes in a live stream from Reddit and analyzes keywords for sentiment using the sentiment package from npm. The data is then graphed using react-easy-charts. React framework is being used.

Working: Comments are successfully being streamed and keywords are being searched, so the main functions are in place.

-Working on cleaning up the app and prettying stuff up

Hosted on Heroku: Check out the working link on Heroku. (The app will take a 10-20 seconds to wake up because of how Heroku works).
You also need to give a few seconds for the reddit api to wake up as well. Comments will stop being streamed after 100 seconds since I don't want to throttle reddit's servers. Will add a "stop streaming" button, but that's low priority.

https://aqueous-retreat-72108.herokuapp.com/


