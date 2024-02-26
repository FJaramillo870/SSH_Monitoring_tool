# Server Monitoring Software
# SSH Monitoring for the BIZON Z500 Deep Learning Workstation
## Introduction
Secure Shell Protocol (SSH) monitoring can be challenging for users due to the need for terminal commands, a connection setup with a username, IP address, and password. To simplify this process, we developed a user-friendly software. This application offers a more intuitive interface, consolidating all data in one place.

## Development Overview
The purpose of this software is to efficiently monitor the BIZON Z500 Deep Learning Workstation for SSH activity. It remotely monitors the workstation, eliminating the need for users to manually run commands. The software, developed using the Bash and Python programming languages and Pandas, Gradio, and SQLite libraries, automatically connects to the server, runs necessary commands, and stores data in a database. This information is then presented on a user-friendly website.

## Key Features
Key features include:

• Automatic connection to the workstation

• Centralized data storage

• Regular updates to the database

• Graphical User Interface (GUI) for easy navigation

## Development Process
During the development process, we prioritized creating the database, followed by the GUI, bash script, and Pandas data frame. The bash script facilitates automatic connection and command execution, while the Pandas data frame organizes the data before it is sent to the database. The data is then displayed using Gradio interface.

## Benefits
Benefits include:

• Database storage for accessing historical records

• Enhanced monitoring efficiency

• User-friendly GUI, eliminating the need for command-line expertise

• Easy data retrieval with a search bar and sorting options

## Conclusion
In conclusion, the primary goal of developing this software was to simplify SSH monitoring for users. This goal has been achieved by enabling remote monitoring without the need for manual command execution. With the Gradio link, users can conveniently access and review past login records.
