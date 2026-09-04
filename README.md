# Incident-Log-Analyzer-
A beginner-friendly Python Log Analyzer that reads a log file, counts INFO, WARNING, and ERROR entries, and displays all error messages. This project demonstrates file handling, functions, loops, dictionaries, lists, and basic exception handling in Python.
# Incident Log Analyzer

## About the Project

Incident Log Analyzer is a simple Python project that reads a log file and analyzes the different types of log entries.

It counts how many `INFO`, `WARNING`, and `ERROR` messages are present in the file. It also displays all the error messages separately.

I made this project to practice Python file handling, dictionaries, lists, loops, conditions, and exception handling.

## Features

- Reads a log file line by line
- Counts `INFO` messages
- Counts `WARNING` messages
- Counts `ERROR` messages
- Displays the total number of log entries
- Displays all error messages
- Handles empty or incorrect log lines
- Handles the case when the log file is not found

## Technologies Used

- Python

## How It Works

The program reads the `app.log` file and separates each line into:

- Date
- Time
- Log level
- Message

For example:

```text
2026-08-20 10:16:02 ERROR Database connection failed
