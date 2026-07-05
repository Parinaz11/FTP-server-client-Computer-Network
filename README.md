# File Transfer Protocol (FTP) Client-Server

This project implements a simple File Transfer Protocol (FTP) system using Python and a Tkinter-based graphical user interface. It was developed as the final project for a Computer Networks course at university.


## Project Overview

The system consists of two components:

- **FTP Server**
- **FTP Client (GUI-based using Tkinter)**

The client communicates with the server through predefined commands to perform basic file operations such as uploading, downloading, and managing files on the server.

---

## How It Works

1. Start the **server application** first.
2. Run the **client application**.
3. A GUI window will open where you can enter commands and view responses from the server.


## Supported Commands

The client supports the following FTP-like commands:

```
HELP
```
Displays a list of available commands and usage instructions.

```
DOWNLOAD <file_path / file_name>
```
Downloads a file from the server.

```
UPLOAD <file_path / file_name>
```
Uploads a file to the server.

```
DELETE <file_path / file_name>
```
Deletes a file from the server.

```
PWD
```
Displays the current working directory on the server.

```
QUIT
```
Closes the client connection.


## Technologies Used

- Python
- Tkinter (GUI)
- Socket Programming
- Basic Client-Server Architecture

---

## Project Purpose

This project demonstrates core concepts of computer networking, including:

- Client-server communication
- Socket programming in Python
- File transfer mechanisms
- Command-based protocol design
- Basic GUI integration with network systems

## Academic Context

This project was completed as the final assignment for the **Computer Networks** course at university.
