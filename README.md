# Chat Room
Chat room application implementation using WebSocket and STOMP with Spring Boot MVC framework.

## Background
### Websocket
WebSocket is a communication protocol that makes it possible to establish a two-way communication channel between a server and a client.

### Message model
Message model is the message payload that will be exchanged between the client and the server. The model provides the following actions.
1. ENTER a chatroom
2. CHAT with other users in the chatroom
3. LEAVE the chatroom

## Requirements
1. JDK
2. Maven
3. Chromedriver for testing

## Instruction
### Run the application with command
mvn build; mvn spring-boot:run

### To test the application
mvn clean test