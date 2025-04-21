# File Organizer Automation Report

## Overview
This project automates the organization of files in a directory by moving them into subdirectories based on their file extensions.

## Features
- Automatically creates appropriate subdirectories
- Handles common file types (images, documents, videos, etc.)
- Places unknown file types in an "Other" directory
- Safe execution (won't move the script itself)

## Usage
1. Clone the repository
2. Run `python organizer.py`
3. Enter the directory path you want to organize (or press Enter for current directory)

## Implementation Details
- Uses Python's `os` module for file operations
- `shutil` module for moving files
- Simple command-line interface

## Future Improvements
- Add logging functionality
- Support configuration file for custom folder mappings
- Add undo functionality
- Create GUI interface
