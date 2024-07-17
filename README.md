# Music Streaming Service Management System

## Objective
This section provides an overview of the project, explaining that the goal is to create a menu-based console application to simulate a music streaming service management system. The application is designed to demonstrate your proficiency in Core Java, MySQL, and JDBC.

## Functionalities
This section lists the main features of the application, which include managing music tracks, artists, and playlists. Each functionality is broken down into specific actions the user can perform, such as adding, viewing, updating, and deleting records.

## Database Schema
This section outlines the structure of the MySQL database tables used in the project. It includes:
- *Music Track Table*: Stores information about music tracks.
- *Artist Table*: Stores information about artists.
- *Playlist Table*: Stores information about playlists.
- *Playlist_Tracks Table*: Manages the relationship between playlists and tracks.
- *User Table*: Stores information about users.

## Requirements
This section lists the technologies and tools required to develop and run the application, which are Core Java, MySQL, and JDBC. It also emphasizes the importance of clean, well-documented code that follows standard coding conventions.

## Setup Instructions
This section provides step-by-step instructions on how to set up the project on a local machine:

### Step 1: Clone the Repository
Instructions for cloning the GitHub repository to your local machine.

### Step 2: Set Up the MySQL Database
Instructions for creating and setting up the MySQL database. This includes creating a new database, importing the database schema, and configuring the database connection.

db.url=jdbc:mysql://localhost:3306/music_streaming
db.username='root'
db.password='Root@123'

### Step 3: Configure Database Connection
Details on how to update the db.properties file with the MySQL database credentials. This file will be used by the application to connect to the database.

### Step 4: Compile and Run the Application
Instructions on how to compile the Java classes and run the application using the MySQL JDBC connector.

## Usage Instructions
This section explains how to use the application once it's set up:

### Launching the Application
Instructions on how to start the application by running the main class Main.

### Navigating the Menu
Guidance on how to navigate the menu options to perform various operations like adding, viewing, updating, and deleting records for music tracks, artists, and playlists.

### Example Code Snippets
Two code snippets are provided as examples of how to list all artists and playlists. These snippets give an idea of the structure of the code and how SQL queries are used to retrieve and display data:

#### Listing All Artists
This method retrieves all artists from the Artists table and prints their details.

#### Listing All Playlists
This method retrieves all playlists and the count of tracks in each playlist from the Playlists and PlaylistTracks tables and prints their details.
