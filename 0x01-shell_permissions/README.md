# Switch User to Betty

This script is designed to switch the current user to the user "betty" on the system.

## Requirements
- This script assumes that the user "betty" already exists on the system.
- The script should be run on Ubuntu 20.04 LTS.

## Usage
1. Ensure that the script has executable permissions: `chmod +x 0-iam_betty`.
2. Execute the script: `./0-iam_betty`.

## Script Details
The script is a simple Bash script consisting of two lines:
1. The shebang line `#!/bin/bash` specifies that the script should be executed using the Bash shell.
2. The command `su betty` switches the current user to "betty".

Please note that this script should be run with appropriate privileges to switch to another user.

Feel free to modify and use the script according to your needs.
