# TaskThree

## Overview

TaskThree is a script for managing Linux user accounts, allowing modification of user information and password changes using `usermod` and `passwd`.

## Prerequisites

- Linux OS (e.g., Kali Linux, Ubuntu)
- Root access

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/taskthree.git
    cd taskthree
    ```
2. Make the script executable:
    ```bash
    chmod +x taskthree.sh
    ```

## Usage

### Modify User Information

Example command to change username, home directory, shell, and add to a group:
```bash
./taskthree.sh -m -u olduser -n newuser -d /home/newuser -s /bin/zsh -g developers
