
# Scala-Project

## Team members:

- Hesham Hassan
- Ibrahim El-sadek
- Malak Magdy

## Steps to run the code:

1. Download the Oracle connector, ojdbc8.jar, and make sure it is accessible.
2. Adjust the `sourceDirPath` and `logFilePath` variables in the code to match the desired paths on your local device.

## Description:

This Scala project consists of a simple application that automates the process of applying business rules to datasets inserted into a specific path. The application processes the inserted file, applies the defined business rules, inserts the transformed data into a database, and finally deletes the file from the source folder. A log file is generated to track the execution details.

## Code Description:

The code can be divided into two main parts:

1. **File Processing and Database Publishing:**
   - The core logic resides in the `processFile` function.
   - Six business rules are applied using separate functions.
   - The `top2` and `calcPrice` functions are utilized to derive the final result.

2. **File Loading and Deletion:**
   - This part of the code handles the loading of files from a directory and deletes them after processing.

Please refer to the source code for more detailed information on the implementation.
