# Social RideSharing App

Android Application that provides ride sharing functionality to chatrooms. Users can put up request for a ride in chatrooms and other uses In that chatroom can respond to that request. Integration of google maps and firebase makes it easier for the rider to see the driver's live location.

![](social-ride-sharing.jpg)

Watch the video demonstrating the workflow of this application below.

![Part1](https://www.youtube.com/watch?v=a-_K_EVyvvA&t=0s) 

![Part2](https://www.youtube.com/watch?v=cIK5y4v27Z4&t=0s) 


Technologies - Android, Java, Firebase Realtime database, Google Maps, Places Autocomplete, Google Directions API, Firebase Storage, Location Manager

Part 2 - https://www.youtube.com/watch?v=cIK5y4v27Z4

- The application provides Authentication and Signup using Firebase Email/Password authentication. In addition it has forgot password feature that sends link to registered email address.
- The user is able to create/edit profile. The data is stored on Firebase Realtime database and user images are stored in Firebase Storage.
-  A user is able to view a list of users in the system and can view their profile information.
-  The user session in stored in shared preferences.  A logged-in use is able to create a chatroom and list the current chatrooms in the system. A user can join a chat room, view the posted messages, and post new messages with the images.
- In a chatroom, the messages is displayed, indicating the message text, date/time of the message, name of user, profile image of the user and number of likes.
- A user can like a message by clicking on a like button displayed by each message. A user can delete messages that he/she created.
-  In a given chat room, a user can request from all the users in the room to provide him with a ride.
Once the user starts typing for the origin and destination locations for ride, the application shows the suggestion of locations in dropdown implemented by Places Autocomplete api from google.
- The users receiving the ride request are alerted and shown a map indicating that a user has requested a ride.  The request includes the current user name, location from which to pickup, and location to drop off.
-  A user requesting a ride receives several pickup offers and are able to choose which request to accept.
-  Upon accepting a ride, the user waiting for the ride is be able to view the progress (location) of the user coming to pick them up on a map showing the pick up location and the driver's realtime location. The live locations of user is tracked using the Location Manger Api in android.
-  Upon being picked up the ride is started and user can see its live location on google maps towards the destination. When the driver drops the user on the destination this marks the completion of the ride.
- A user is able to view their previous rides, and shown as much as possible of the trip details.


