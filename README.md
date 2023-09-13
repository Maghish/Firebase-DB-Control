# Firebase-DB-Control

## Simple Description:
This is a python project which you can setup and make automatted Firebase DB. Read the README.md file for more information.

## Detailed Description:
Using this project, you can build automatted fetch&push system for Firebase Database. This project basicially inherits `firebase-admin` module. But this project provides some functions like `JSONPushDelay` which pushes data from local JSON files to firebase database in delayed timing. Firebase's Database is a no-sql database, which has same syntax/structure like JSON files. So the idea is... if you think of using Firebase Database as your Database, then you can store data and retreive data using JSON files which we can count as temp and every 10 mins or the given delay, the program will push the data from the temp files to the firebase database. even though JSON is not a good database or not even a database, it's better to use JSON this way if you want to use the firebase database. You can also add and delete values manually and stuff. 


