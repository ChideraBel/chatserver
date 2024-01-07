This is the API that handles the websocket communication for this chat web page: https://github.com/ChideraBel/chat-app.

Run:  - mvn spring-boot:run (in the spring-ws-server) before starting the webpage on react. 

Updates: Added image sharing functionality for emojis and small pictures. Since STOMP only allows text messages, images are encoded to base64 and sent through the server.
