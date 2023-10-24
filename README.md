Custom Netcat in Python

Introduction

This project is a custom Netcat implementation in Python, designed for learning socket programming. Netcat is a versatile networking utility that allows you to read from and write to network connections using the TCP/IP protocol. This project provides a basic example of how to create a simple Netcat-like tool in Python.
Features

    Server and client functionality.
    Basic command execution on the server from the client.
    Graceful handling of connections and exits.
    Open-source and ready for further customization and expansion.

Prerequisites

Before you get started with this project, make sure you have the following prerequisites:

    Python 3.x installed on your system.

Getting Started

    Clone the repository to your local machine:

    

git clone https://github.com/nipunnegi2/myownnetcat.git

Open two terminal windows.

In one terminal, navigate to the project directory and run the server.py script:



    python server.py

In the other terminal, navigate to the project directory and run the client.py script:


    python client.py

Usage

Once the server and client are both running, you can use the client to send commands to the server. Here's a basic example:

    In the client terminal, you'll see the "Connected" message.

    Enter a command like "ls" or "pwd" and press Enter. The server will execute the command and send the output back to the client.

    To exit the client, simply enter "exit" and press Enter.

License

This project is licensed under the MIT License.
Contributing

If you'd like to contribute to this project, please follow the Contribution Guidelines.
Acknowledgments

    This project was created for educational purposes to learn more about socket programming in Python.

Contact

If you have any questions or suggestions, please feel free to contact the project maintainer at nipunnegi2002@gmail.com
Disclaimer

This project is for educational and learning purposes only. Use it responsibly and with proper authorization. The authors are not responsible for any misuse of this software.
