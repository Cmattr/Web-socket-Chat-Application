Chat Application.
Welcome to The WebSocket Chat App. This App is designed for multiple users to be able to chat back and forth.
1. SignIn/HomePage: Displays a text box for that is indicated by the title username and a Login button. The login button will direct you to the chatroom after you have entered a username longer than 6 characters
2. ChatRoom: The Chatroom is where the user will be able to send and recieve messages. Simply type your message into the textbox and hit enter to send. After sending a message the message will be displayed in the
   chat body along with the username the user signed in with, a timestamp and a delete button. To delete a specific message click the delete button and the chosen message will be removed.
   The Log Out button located at the top of the screen will return you to the homepage.

- Installation and Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/cmattr/Web-socket-Chat-Application.git
    ```
2. Navigate to the project directory:
```sh
  cd Web-socket-Chat-Application
```
3. to start the application you open two seperate terminals.
   In the first terminal cd into the M15-L2-Websockets folder and then use flask run to begin running the Backend Server
```sh
    cd M15-L2-Websockets
    flask run
```
  In the second terminal cd into the web-socket-chat react application and then use npm start to begin running the application
```sh
    cd web-socket-chat
    npm start
```
