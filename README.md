
# Online Voting System

## Overview

This project is an online voting system application developed during my diploma program to explore the implementation of voting mechanisms using Java and databases. The system is designed to streamline the voting process while ensuring security and transparency. Users can register, log in, cast their votes, and view election results.

## Features

1.  **User Registration**:
    -   Users can register by providing necessary details such as name, voter ID, and a secure password.
2.  **Authentication**:
    -   Registered users can log in using their credentials for security.
3.  **Voting Functionality**:
    -   Users can cast their votes in an election.
    -   Each user is allowed to vote only once.
4.  **Admin Panel**:
    -   Admins can manage the election process, add candidates, and view results.
5.  **Result Display**:
    -   The system displays the election results once the voting period ends.

## Project Structure

The code is modular, organized into classes representing different roles and functionalities:

-   **Voter**: Handles user registration, login, and voting.
-   **Admin**: Manages candidate addition, monitors voting progress, and displays results.
-   **DatabaseHandler**: Ensures secure and efficient storage and retrieval of user and election data.
-   **VotingSystem**: Provides the main application logic for coordinating all components.

## Getting Started

### Prerequisites

-   **Java JDK**: Ensure you have Java Development Kit installed.
-   **Database**: A database like MySQL or SQLite for data storage.
-   **Maven/Gradle**: If using external libraries, ensure Maven or Gradle is set up.

### How to Run

1.  **Clone the Repository**:
    
    ```bash
    git clone https://github.com/yourusername/OnlineVotingSystem.git
    
2.  **Navigate to the Project Directory**:
    
    ```bash
    cd OnlineVotingSystem
    
3.  **Compile the Code**:
    
    ```bash
     javac -d bin src/*.java
    
4.  **Run the Application**:
    
     ```bash
      java -cp bin VotingSystem`
    
6.  **Set Up Database**:
    
    -   Import the provided SQL script (`schema.sql`) into your database.
    -   Update database connection details in the `DatabaseHandler` class.

## Usage

1.  **Admin Login**:
    -   Admins can log in to add candidates, manage elections, and view results.
2.  **User Registration**:
    -   New users can register by entering their details.
3.  **Voting**:
    -   Registered users log in, view the list of candidates, and cast their vote.
4.  **Results**:
    -   Results can be viewed after the election ends, displaying the winner and vote counts.

## Future Enhancements

1.  **Multi-Language Support**:
    -   Add support for multiple languages to cater to diverse users.
2.  **Enhanced Security**:
    -   Implement advanced security measures such as biometric authentication and blockchain-based voting.
3.  **Mobile Application**:
    -   Develop a mobile version for better accessibility.
4.  **Real-Time Voting Statistics**:
    -   Display live updates of voting trends during the election period.


#Author: Arman Sayyed