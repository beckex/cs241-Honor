Progress:
Week Nov2 - Nov 8 The group meet together, decided to build an app to connect to nearby people. The app should get geometric infromation from user and upload it to our database. The app then search for devices within certain area. 

Hackthon - Nov15 We seperated the team into two parts, one response for the android java part, other part reponse for the NDK jni part. The android java part made up the user interface for the app and used the Android api's to get the position information for the app. The java part also managed to connect to the database to upload the position information and the status of each user posted. Then the java part pass the position information to the jni part. The jni part received the information and use multithread to calcualte the distance between each users, if the distance is less than some certain threshold, eg. 10m, both user would receive the status message of each other and complete a "passby action". The app would send the request for update the positon information every 3 seconds. We finished the java part and jni part seperately during the hackthon.

Dec 6,7 Final debug to make our app run. 

Problems faces:
Writing c code in android project is realing challenging. The process to connvert from java type variable to c type need proper funciton calls, which are hard to remember. Another problem is how to connect to database from our app. 

Thoughts:
The project is done greatly but our group can do better at efficiency. In the SQL query part to find nearby devices, for example, we could roughly filter devices instead of simply retrieve all devices at one query. This method could make our app download less data from server and use less cpu/ram resouces, since the server do some work that would otherwise be done by the mobile device.
