# UD-VIPStream

UD-VIPStream is a Java-based application that provides a platform for streaming and managing video content, similar to Netflix. The application operates on a client-server model, facilitating communication and media exchange between users.

## Features

- **User Management**: Manages user sessions and authentication, ensuring secure access to the application.
- **Video Streaming**: Enables users to stream video content in real-time.
- **Actor Management**: Allows association of actors with specific video content.
- **Content Management**: Provides functionalities to manage and organize video content.
- **Server-Client Communication**: Utilizes Java sockets for robust server-client communication.
- **Graphical User Interface**: Offers a user-friendly interface for easy interaction with the application.

## Some Technical Details

- **Java Sockets**: Used for implementing the server-client communication, enabling real-time data exchange and seamless interaction between the user interface and the server.
- **Java Swing**: Utilized for creating the graphical user interface, providing a visually appealing and user-friendly experience.
- **Content and Actor Management**: Supports adding, removing, and updating video content and associated actors.
- **Server-Side Operations**: The `Servidor` class handles server-side operations, managing connections, users, and media content.
- **Database Integration**: The application interacts with a database to store and retrieve user data and media content, ensuring data persistence.

## License

This project is open-source and available under the [MIT License](LICENSE).
