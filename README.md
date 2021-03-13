Application deployed at: https://budget-tracker-jb.herokuapp.com/

# Unit 18 PWA Homework: Online/Offline Budget Trackers
This application is a budget tracker that is able to be accessed and used offline. The user is able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the transaction is completed and stored in a database when brought back online.


## Updates
I made changes to an existing budget tracker to make it a Progressive Web Application. I created or modified the following files:
### manifest.json
This json contains the necessary information to allow a web application and set it up as a mobile application such that it can be displayed/stored on a mobile home screen. 

### service-worker.js
This is the code for a service worker. It caches input information in the browser while offline. 

### db.js
This code contains the handling of offline data and moves it from the cache to the db when connected

### index.js and index.html
These were updated to call service worker and connect to the manifest.json

