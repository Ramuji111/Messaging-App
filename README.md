# Messaging App

Messaging App is a simple client-server chat application implemented in Python, allowing users to create and join groups, send messages, manage group membership, and share files within the group.

## Features

- **Group Creation and Joining**: Users can create new groups or join existing ones.
- **Message Sending**: Users can send text messages to all members of the group.
- **Group Membership Management**: Admins can approve join requests, view and manage group members, and transfer adminship.
- **File Sharing**: Users can share files with other group members.
- **Interactive Command-Line Interface**: Both server and client have interactive command-line interfaces for user interaction.

## Installation

### Prerequisites

- Python 3.x

### Server Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Ramuji111/Messaging-App.git
    ```

2. Navigate to the `server` directory:

    ```bash
    cd server
    ```

3. Run the server:

    ```bash
    python server.py <IP> <Port>
    For Example- python server.py localhost 8000
    ```

   Replace `<IP>` and `<Port>` with the IP address and port number you want the server to listen on.

### Client Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Ramuji111/Messaging-App.git
    ```

2. Navigate to the `client` directory:

    ```bash
    cd client
    ```

3. Run the client:

    ```bash
    python client.py <IP> <Port>
    For Example- python client.py localhost 8000
    ```

   Replace `<IP>` and `<Port>` with the IP address and port number of the server.

## Usage

1. Start the server as described in the Server Setup section.
2. Start the client as described in the Client Setup section.
3. Follow the instructions on the client command-line interface to interact with the chat application.

## Acknowledgments

- Inspired by [PyCon](https://www.python.org/community/pycon/).
- Built using Python's `socket` and `threading` modules.
