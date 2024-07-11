# Video File Processing and Torrent Management System

This system is designed to handle video file processing and manage torrents efficiently. It includes functionality for removing video file extensions, comparing video file names, and managing torrents within specified categories.

## Features

- **Video File Extension Removal**: Automatically detects and removes common video file extensions from file names.
- **Name Comparison**: Compares two video file names by removing their extensions and calculating the similarity based on the intersection of words in their names.
- **Torrent Management**: Connects to a torrent client, reads cache, and processes torrents based on their categories. It also filters torrents by excluding specific categories and tags.

## Requirements

- Python 3.x
- Libraries: `re` for regular expressions

## Setup

1. Ensure Python 3.x is installed on your system.
2. Clone this repository or download the source code.
3. Install required Python libraries (if any are specified).

## Usage

1. Update the `QB_URL`, `QB_USERNAME`, and `QB_PASSWORD` variables with your torrent client's URL, username, and password.
2. Define the categories you want to manage in the `CAT_NAMES` variable.
3. Run the script using Python:

```bash
python script.py
