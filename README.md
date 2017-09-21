# multiPacman
A multiplayer game: which behave like a distributed system. It’s based on the classic Pacman game and rules. The main object of this project was handling the common problems that arises when removing the centralizing component from the system: for instance the Consensus problem.

## Requirements
1. Java: You can download and install it from (https://java.com/en/)
2. To make the system distributed we used The Java Remote Method Invocation API (RMI)

## Run the system
1. Compile all the .java files in src/. In bin/ you already have the compiled versions (.class)
2. Run the AuthServer: ```java AuthServer```. This component is the server of the game and it will authenticate and register the players willing to participate to the game.
3. Each player willing to partecipate need to run: ```java Node```. This will open the game window with a white textBox where he must type the IP of the AuthServer host.
4. The game starts after the host server receives the wanted number of players

![](Screen.png?raw=true "The game")
