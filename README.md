cs241-Honor
===========
A social networking app that exchange data with the people you passed by, something like the Nintendo 3DS's StreetPass fucntionality. We would use websocket to transfer the information and connect the phone to the sever. When we sending request and receving request from server, we would deal with the issue like reader writor problem. That's how we solve the synchrinaztion issues.

Week Nov2 - Nov 8
    The group meet together, discussed the whole project plan and generally distributed the work to the group members. Discussed some general issues about the hackthon. 
    

Hackthon - Nov15
  We seperated the team into two parts, one response for the android java part, other part reponse for the NDK jni part. The android java part made up the user interface for the app and used the Android api's to get the position information for the app. The java part also managed to connect to the database to upload the position information and the status of each user posted. Then the java part pass the position information to the jni part. The jni part received the information and use multithread to calcualte the distance between each users, if the distance is less than some certain threshold, eg. 10m, both user would receive the status message of each other and complete a "passby action". The app would send the request for update the positon information every 3 seconds. We finished the java part and jni part seperately during the hackthon.
  
  
