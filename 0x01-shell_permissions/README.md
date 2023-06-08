# Shell Permissions Scripts

This repository contains a collection of shell scripts that demonstrate various tasks related to file permissions and ownership. Each script performs a specific action, such as changing permissions, modifying ownership, or executing commands on files and directories.

## List of Scripts

1. **0-iam_betty**: Switches the current user to the user 'betty'.
2. **1-who_am_i**: Prints the effective username of the current user.
3. **2-groups**: Prints all the groups the current user is part of.
4. **3-new_owner**: Changes the owner of the file 'hello' to the user 'betty'.
5. **4-empty**: Creates an empty file called 'hello'.
6. **5-execute**: Adds execute permission to the owner of the file 'hello'.
7. **6-multiple_permissions**: Adds execute permission to the owner and group owner, and read permission to other users, to the file 'hello'.
8. **7-everybody**: Adds execution permission to the owner, the group owner, and other users, to the file 'hello'.
9. **8-James_Bond**: Sets the permission to the file 'hello' as follows: Owner - no permission, Group - no permission, Other users - all permissions.
10. **9-John_Doe**: Sets the mode of the file 'hello' to '-rwxr-x-wx'.
11. **10-mirror_permissions**: Sets the mode of the file 'hello' the same as the mode of the file 'olleh'.
12. **11-directories_permissions**: Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.
13. **12-directory_permissions**: Creates a directory called 'my_dir' with permissions 751 in the working directory.
14. **13-change_group**: Changes the group owner to 'school' for the file 'hello'.
15. **100-change_owner_and_group**: Changes the owner to 'vincent' and the group owner to 'staff' for all files and directories in the working directory.
16. **101-symbolic_link_permissions**: Sets the permission of a symbolic link named 'my_link' to be the same as the file it points to.
17. **102-if_only**: Checks if the file 'hello' exists and displays a message based on the result.
18. **103-Star_Wars**: Displays an ASCII art of the Star Wars logo in the terminal.

## Usage

To run any of the scripts, navigate to the repository directory on your system and run.


Make sure to provide the necessary permissions to execute the scripts if needed.
