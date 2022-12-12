
## Project: Shell, basics
### Description:
File permission management scripts.
### Learning objectives:
#### Permissions

-   What do the commands `chmod`, `sudo`, `su`, `chown`, `chgrp` do
-   Linux file permissions
-   How to represent each of the three sets of permissions (owner, group, and other) as a single digit
-   How to change permissions, owner and group of a file
-   Why can’t a normal user `chown` a file
-   How to run a command with root privileges
-   How to change user ID or become superuser
### Tasks:
| File                                                                                                                       | Description                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [0-iam\_betty](https://github.com/IHansen225/shell/blob/master/permissions/0-iam_betty)                                    | Create a script that switches the current user to the user betty.                                                                                                                    |
| [1-who\_am\_i](https://github.com/IHansen225/shell/blob/master/permissions/1-who_am_i)                                     | Write a script that prints the effective username of the current user.                                                                                                               |
| [10-mirror\_permissions](https://github.com/IHansen225/shell/blob/master/permissions/10-mirror_permissions)                | Write a script that sets the mode of the file hello the same as olleh’s mode.                                                                                                        |
| [11-directories\_permissions](https://github.com/IHansen225/shell/blob/master/permissions/11-directories_permissions)      | Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed. |
| [12-directory\_permissions](https://github.com/IHansen225/shell/blob/master/permissions/12-directory_permissions)          | Create a script that creates a directory called my\_dir with permissions 751 in the working directory.                                                                               |
| [13-change\_group](https://github.com/IHansen225/shell/blob/master/permissions/13-change_group)                            | Write a script that changes the group owner to school for the file hello                                                                                                             |
| [14-change\_owner\_and\_group](https://github.com/IHansen225/shell/blob/master/permissions/14-change_owner_and_group)      | Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.                                            |
| [15-symbolic\_link\_permissions](https://github.com/IHansen225/shell/blob/master/permissions/15-symbolic_link_permissions) | Write a script that changes the owner and the group owner of \_hello to vincent and staff respectively.                                                                              |
| [16-if\_only](https://github.com/IHansen225/shell/blob/master/permissions/16-if_only)                                      | Write a script that changes the owner of the file hello to vincent only if it is owned by the user guillaume.                                                                        |
| [2-groups](https://github.com/IHansen225/shell/blob/master/permissions/2-groups)                                           | Write a script that prints all the groups the current user is part of.                                                                                                               |
| [3-new\_owner](https://github.com/IHansen225/shell/blob/master/permissions/3-new_owner)                                    | Write a script that changes the owner of the file hello to the user betty.                                                                                                           |
| [4-empty](https://github.com/IHansen225/shell/blob/master/permissions/4-empty)                                             | Write a script that creates an empty file called hello.                                                                                                                              |
| [5-execute](https://github.com/IHansen225/shell/blob/master/permissions/5-execute)                                         | Write a script that adds execute permission to the owner of the file hello.                                                                                                          |
| [6-multiple\_permissions](https://github.com/IHansen225/shell/blob/master/permissions/6-multiple_permissions)              | Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.                                                 |
| [7-everybody](https://github.com/IHansen225/shell/blob/master/permissions/7-everybody)                                     | Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello                                                                   |
| [8-James\_Bond](https://github.com/IHansen225/shell/blob/master/permissions/8-James_Bond)                                  | Write a script that sets the permission to the file hello                                                                                                                            |
| [9-John\_Doe](https://github.com/IHansen225/shell/blob/master/permissions/9-John_Doe)                                      | Write a script that sets the mode of the file hello                                                                                                                                  |
