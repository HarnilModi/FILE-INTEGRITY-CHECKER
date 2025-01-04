**Name:** HARNIL MODI

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08DAN

**Domain:** Cyber Security & Ethical Hacking

**Duration:** December to January 2025

**Mentor:** Neela Santhosh Kumar



## **Overview of the Project :-** 


### Project :- FILE INTEGRITY CHECKER.

## Objective
The goal of this project is to develop a File Integrity Checker tool that ensures the security and consistency of files by monitoring changes in their content. The tool calculates and compares hash values to detect any modifications, deletions, or additions in files within a specified directory.

## Key Features
1.Hash Calculation:

Calculates hash values (e.g., SHA-256, MD5) for files to establish a baseline for integrity checks.

2.Change Detection:

Detects changes in file content by comparing current hash values with stored hashes.

Identifies and reports unchanged, modified, or missing files.

3.Customizable Hash Algorithm:

Supports multiple hashing algorithms (default: SHA-256) to meet varying security requirements.

4.File Monitoring:

Scans all files in a specified directory and generates a JSON file containing hash values.

5.Logging:

Logs activities, errors, and results into a log file (file_integrity.log) for audit purposes.

6.User-Friendly Interface:

Provides an interactive console-based interface with options to generate hashes or check integrity.

7.Progress Bar:

Displays a progress bar for file processing to enhance user experience.

8.Error Handling:

Handles errors gracefully, such as missing files or invalid directory paths.

9.Output Reports:

Generates a summary report of integrity check results, including counts of unchanged, changed, and missing files.

## Technologies Used
**Programming Language:** Python

**Libraries:**

-hashlib: For cryptographic hash calculations.

-os: To interact with the file system.

-json: For storing and reading hash values in JSON format.

-tqdm: For displaying progress bars during file operations.

-logging: For activity tracking and debugging.



## How to Run:
**Install tqdm using pip:**

pip install tqdm

**Generate Hashes:**

Run the script and choose option 1.

Provide the directory path you want to monitor.

Hashes of all files in the directory will be stored in a JSON file (default: file_hashes.json).

**Check Integrity:**

Run the script again and choose option 2.

Provide the same JSON file used during hash generation.

The script will compare the current hashes with the stored ones and report:

Files that have changed.

Files that are missing.

Files that are unchanged.

![Screenshot 2025-01-04 163949](https://github.com/user-attachments/assets/e70026c1-ce4a-4add-bf03-505afcd35fe0)
