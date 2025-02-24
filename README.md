Download Link :https://programming.engineering/product/csci-4311-5311-socket-programming-assignment-2/


# CSCI-4311-5311-Socket-Programming-Assignment-2
CSCI 4311/5311 Socket Programming Assignment 2
Goal of the assignment

In this assignment, we build a Multiplayer game.

Choose a game which can be played with at least 2 players.

You can choose any game you want. It is totally up to you.

Example games that you can implement: Chess, Backgammon, GO, UNO, Poker

I give Tic Tac Toe (XOX) game as an example below. You are NOT allowed to implement that game. Choose another game.

You can modify the multithreaded server that you implemented in Assignment 1.

Rules:

The server must be able to monitor and handle messages from multiple clients simultaneously. Therefore, your server needs to be multithreaded.

Do NOT implement a peer-to-peer application. E.g., clients talk directly to each other.

The architecture here is server-client. All messages and actions from the clients go through the server. The server distributes the messages to all other clients who have a connection to the server.

Implement the assignment with Java

You need to write a report to explain your code, put some screenshots for your outputs, etc. Save your report in PDF format.

Without the report, you don’t get any points.

GUI is optional with 20 bonus points. If you implement the GUI version well, you will get an additional 20 points.

Put your code and report in a folder, Compress the folder and submit the compressed folder. Do NOT submit separately.

Here is an Example GAME: Tic Tac Toe (XOX)

1- Start the Server which listens port number 5000.

2- Server waits 2 users. When the user joins the game, server asks a username.

3- Start client 1, provide a username. E.g. Player X

4- Client 1 waits until the second player joins the game.

5- Client 2 enters, provide a username, e.g. Player O

6- Server sends the initial table to both players


7– Assume that player X choose 5, X sends a message to the server. Server sends updated table to both players.


8– Assume that player O choose 1;


9– The game continues until one of the player wins or draw case.

10– If a player sends a position without his/her turn, server sends an error message to the player “It is not your turn”.
