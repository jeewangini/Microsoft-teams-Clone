Microsoft Teams Clone
A mobile Application used for chatting and video calling.I used flutter as the platform and Android Studio as the IDE.

Getting Started
This application enables users to connect via chats and video calls.
Design Considerations
Assumptions and Dependencies:
Internet Connectivity
Android Version 9 and above
General Constraints
Not more than 7 people can join the meet at a time.
Development Methods
Authentication and log in using google services
Chat messaging using firebase
Video  calling using Agora SDK
token generation server for video calling using Node.js
Detailed System Design
Upon opening the app, the user based on whether is already logged in dashboard or login screen is shown.
Login Screen 
Users can log in using their email and password. if the user has forgotten the password, they can reset it using the forgot now selection where the link to reset the password is sent via mail. The new users can register using the register now feature.
After logging in the user lands on the dashboard. The dashboard has three tabs:
login1.png
Chat View: all the previous chats the user has had are shown here. An option is provided to search for the user and initiate a chat. also if the user has no chats an option is given to initiate a chat with a demo account where later a chatbot can be implemented.
login1.png
In the conversation screen, the chats between the users are displayed. Also, an option is given to initiate a call where the users can continue the conversation and retain them in the chats.
hehe.png
2.Group View: all the groups user is a part of are shown here. An option is provided to create a group and add users to it by searching them by their user names.
login1.png
In the conversation Screen, the chats between the users are shown. Also, an option is given to initiate a call where the users can continue the conversation and retain them in the chats.
hehe.png
3.Meet View: here the user is given an option to host a meeting to join a room. To host a meet the user has to enter a room name using which the other users can join in the room.
login1.png
in the join via code feature the user can join as an audience or participant audience can just view and not participate in the call or chat.
In the dashboard, the user is also given an opinion to log out of the account and to view the user details.
hehe.png
