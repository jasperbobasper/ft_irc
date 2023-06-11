# ft_irc - Developing a Reliable IRC Server

In the ft_irc group project, we built an IRC (Internet Relay Chat) server using C++ 98. Our objective was to create a high-performance server capable of handling multiple clients simultaneously. Throughout the project, I gained valuable knowledge and skills in server-side programming, network communication, and error handling. Key highlights include:

  - IRC Server Development: We implemented an IRC server from scratch, adhering to IRC protocols and standards. Our server facilitated communication between clients, supporting features like authentication, nickname management, channel creation, and private messaging.
  - Non-blocking I/O Operations: To ensure responsiveness and scalability, we utilized non-blocking I/O operations. This approach allowed us to handle multiple clients efficiently without blocking the server's execution, resulting in a highly performant IRC server.
  - TCP/IP Communication: We established communication between the server and clients using TCP/IP, enabling reliable data transmission. Understanding the fundamentals of network programming and socket communication was crucial for building a stable and secure server-client architecture.
  - User and Channel Management: Our server featured user authentication, nickname registration, and differentiated privileges between operators and regular users. We also implemented comprehensive channel management functionality, including joining channels, sending messages, and operator-specific commands like KICK, INVITE, TOPIC, and MODE.
  - Error Handling and Testing: Throughout the development process, we focused on error handling and performed extensive testing. We addressed scenarios such as partial data reception, low bandwidth, and edge cases to ensure the server handled all situations gracefully.
  - Clean and Maintainable Code: We prioritized writing clean, readable, and modular code so as to keep the project collaboration smooth. 
  - We also completed a bonus feature and implemented an extremely simple bot that should be ran concurrently to the irc server

##Usage 
  - run `make`
  - chmod +x ircserv
  - `./ircsev <port> <password>`
  - for best results it is recommended to use an irc client such as Pidgin or Adium to connect to the server, however you can use any method you like to join :) 
