
# Java RMI Authentication System

## Overview

This project implements a simple authentication system using Java RMI (Remote Method Invocation). It consists of two main components: `Client` and `Server`.

## Components

### 1. Flash
The Flash class serves as a splash screen before launching the main Client application. It includes a progress bar and transitions to the main window upon completion.

### 2. Client

The `Client` class represents the user interface for interacting with the authentication system. Users can enter server details, user ID, and password to initiate the authentication process.

### 3. Server

The server-side logic involves remote authentication through RMI. A class named `CheckLogin` implements the `LoginInterface` for checking user credentials remotely.


## Usage

1. Run the Flash class to display the splash screen.
2. Enter server details, user ID, and password in the Client window.
3. Click the "GO" button to initiate authentication with the server.
4. 'Hello' message will be shown.

## Dependencies

- Java RMI



