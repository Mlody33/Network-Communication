# Network Comunication Server

_That application was created to improve my skills in programing using i.a._ **OOP, GIT, Clean Code**

Server application expecting clients to connect. Once connected, server have the ability to communicate with clients via TCP on port 5588.

The received command from the client is processed on the server side and the modified data is returned to the client.

# Network Comunication Client

Client application can connect to server but if we want have full access we need authorize app by typing authorization code from server app.

If you pass this process you can update your status by clicking suitable button.

Also you have preview for your app status.



>**_App is still in beta, but mostly works well._**

# Commands for Maven

Build server application and run jar file
>**mvn clean install exec:java**

Build client application and run jar file
>**mvn clean install assembly:single exec:java**


