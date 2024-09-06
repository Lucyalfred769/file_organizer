# file_organizer

## Overview

This Bash script automates the organization of files based on their extensions. It sorts files into categorized directories and logs the actions taken.

## Features

- **Automatic File Organization**: Moves files into folders such as `Images`, `Documents`, `Videos`, `Music`, and `Archives` based on their extensions.
- **Logging**: Keeps a record of all actions and any duplicate files in `log.txt`.

## Prerequisites

- Bash shell
- Basic command-line knowledge

## Installation

1. **Download the Script**:
    Clone or download the script file to your local machine.

2. **Make the Script Executable**:
    ```bash
    chmod +x organize.sh
    ```

## Usage

1. **Run the Script**:
    ```bash
    ./organize.sh
    ```

## Script Breakdown

1. **Directory Setup**:
    The script ensures that an `organized_files` directory exists, creating it if necessary.

2. **File Movement**:
    Files are moved to directories based on their extensions. `.sh` files are skipped to avoid moving scripts.

3. **Duplicate Check**:
    After moving files, the script checks for duplicates and logs any findings.

## Example Output

- **Log File (`log.txt`)**:
    ```
    Moved example.jpg to Images
    Moved report.pdf to Documents
    ```

## Troubleshooting

- **Script Not Running**: Ensure the script has execute permissions (`chmod +x organize.sh`).
- **Missing Files or Directories**: Verify that the script is in the correct directory and has the appropriate permissions.

## Learning Journey

This project introduced me to the practical aspects of Bash scripting, including file manipulation and logging. Automating file organization is a great way to understand real-world scripting applications and improve scripting skills.
