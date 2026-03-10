# Duplicate File Remover

A Python tool that finds and removes duplicate files from a folder using file hash comparison.

## What this program does

This script scans all files inside a folder and identifies duplicate files by comparing their hash values.

If duplicate files are found, the program removes them automatically.

## Features

- Scans an entire directory
- Detects duplicate files
- Uses hash comparison for accuracy
- Removes duplicate files automatically

## Technologies Used

Python

Modules:
- os
- hashlib

## How to Use

1. Run the script.
2. Enter the folder path.
3. The program will scan the folder.
4. Duplicate files will be detected and removed.

## Example

Before running the script:

folder/
file1.txt  
file1_copy.txt  

After running the script:

folder/
file1.txt
