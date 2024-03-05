# Mileo System

Mileo System is a Python application that provides a command-line interface for managing a virtual file system. It allows users to create directories, list contents, display file contents, remove files, and upload files with partitioning.

## Features

- `mkdir`: Create a directory in the file system (e.g., `mkdir /user/john`).
- `ls`: List the content of a given directory (e.g., `ls /user`).
- `cat`: Display the content of a file (e.g., `cat /user/john/hello.csv`).
- `rm`: Remove a file from the file system (e.g., `rm /user/john/cars.csv`).
- `put`: Upload a file to the file system with a specified number of partitions (e.g., `put hello.csv /user/john 3`).
- `getPartitionLocations`: Return the locations of partitions of the file (e.g., `getPartitionLocations /user/john/cars.csv`).
- `readPartition`: Return the content of a specific partition of the specified file (e.g., `readPartition /user/john/cars.csv 2`).

## Installation

1. Ensure you have Python 3 installed on your system.
2. Clone this repository to your local machine.
3. Install the required packages:

   ```bash
   pip install requests
