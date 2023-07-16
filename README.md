# ft_irc - C++ Based IRC Server

Ft_irc is a group project, aiming to build an IRC (Internet Relay Chat) server using C++ 98. 

## Development Process and Features:
  - We implemented the IRC server from scratch, adhering to IRC protocols and standards. The server facilitates communication between clients, supporting features like authentication, nickname management, channel creation, and private messaging.
  - The server utilises non-blocking I/O operations to assure scalability and smooth operation.
  - We use TCP/IP to establish connection, enabling reliable data transmission. Understanding the fundamentals of network programming and socket communication was crucial for building a stable and secure server-client architecture.
  - Our server features user authentication, nickname registration, and differentiated privileges between operators and regular users. We also implemented comprehensive channel management functionality, including joining channels, sending messages, and operator-specific commands like KICK, INVITE, TOPIC, and MODE.
  - Error Handling and Testing: Throughout the development process, we focused on error handling and performed extensive testing.
  - Clean and Maintainable Code: We prioritized writing clean, readable, and modular code so as to keep the project collaboration smooth. 
  - We also completed a bonus feature and implemented an extremely simple bot that should be run concurrently to the irc server

## Usage:
  - run `make`
  - chmod +x ircserv
  - `./ircsev <port> <password>`
  - for best results it is recommended to use an irc client such as Pidgin or Adium to connect to the server, however you can use any method you like to join :) 

## Personal Thoughts on the Project:

I went into this project not even knowing what an IRC server was, and by the end of it I could have probably gotten a decent programming job in the 90's

This project involved a LOT of reading the original IRC protocols, legacy code and studying sockets and networking. 
There are very few public IRC servers still maintained, so even joining one to be able to learn the usage of commands and what responses exist proved challenging (I was kicked from many servers for spam... oops.)

My personal contribution was mostly error management/error handling, some server command implememntation, testing, and the extremely last-minute implementation of the world's simplest bot: 
The party bot. Party bot joins the server, creates a party channel and welcomes anyone who joins to the party. If the word "party" is mentioned, it says "did someone say party?!" 
Yeah... that's it. I dont think my teammates shared my sense of humor but the bonus points requirement simply listed "The server has a bot", so I think they were happy to get the extra point. 