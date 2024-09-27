# Tasknine

This repository contains the updated files from Task Three, including an HTML file and a Python script. The files have been edited using VSCodium, with improvements made to the HTML structure and a shebang added to the Python script.

## Contents

- **index.html**: The improved HTML file with valid syntax and enhancements.
- **script.py**: The updated Python script with a shebang for executable permissions.

## Tools Used

- **VSCodium**: An open-source code editor used to edit and enhance the HTML and Python files.
- **Emmet**: A plugin integrated into VSCodium that helps in writing HTML and CSS faster and more efficiently.

## Installation Instructions

### VSCodium Installation on Kali Linux

To install VSCodium, run the following commands in your terminal:

```bash
echo "deb [arch=amd64] https://github.com/VSCodium/vscodium/releases/download/1.74.3/ vscodium main" | sudo tee /etc/apt/sources.list.d/vscodium.list
wget -qO - https://git.io/vscodium-key.gpg | sudo apt-key add -
sudo apt update
sudo apt install codium
```

For more details, check the [VSCodium GitHub page](https://github.com/VSCodium/vscodium#installation).

## Improvements Made

### HTML File
- Enhanced structure for better readability.
- Validated HTML syntax using Emmet for faster coding.

### Python Script
- Added a shebang line: `#!/usr/bin/env python3` for portability.
- Made the script executable by changing its permissions.

## Running the Python Script

To run the Python script without explicitly using the Python command, follow these steps:

1. Make the script executable:
   ```bash
   chmod +x script.py
   ```
   
2. Execute the script:
   ```bash
   ./script.py
   ```

