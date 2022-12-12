## Project: Shell, basics
### Description:
Bash shell basic commands for file management.
### Learning objectives:
#### What is the Shell

-   What is the shell
-   What is the difference between a terminal and a shell
-   What is the shell prompt
-   How to use the history (the basics)

#### Navigation

-   What do the commands or built-ins `cd`, `pwd`, `ls` do
-   How to navigate the filesystem
-   What are the . and .. directories
-   What is the working directory, how to print it and how to change it
-   What is the root directory
-   What is the home directory, and how to go there
-   What is the difference between the root directory and the home directory of the user root
-   What are the characteristics of hidden files and how to list them
-   What does the command `cd -` do

#### Looking Around

-   What do the commands `ls`, `less`, `file` do
-   How do you use options and arguments with commands
-   Understand the ls long format and how to display it
-   What does the `ln` command do
-   What do you find in the most common/important directories
-   What is a symbolic link
-   What is a hard link
-   What is the difference between a hard link and a symbolic link

#### Manipulating Files

-   What do the commands `cp`, `mv`, `rm`, `mkdir` do
-   What are wildcards and how do they work
-   How to use wildcards

#### Working with Commands

-   What do `type`, `which`, `help`, `man` commands do
-   What are the different kinds of commands
-   What is an alias
-   When do you use the command help instead of man

#### Reading Man Pages

-   How to read a man page
-   What are man page sections
-   What are the section numbers for User commands, System calls and Library functions

### Tasks:

| File                                                                                                                                                    | Description                                                                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [0-current\_working\_directory](https://github.com/IHansen225/shell/blob/master/basics/0-current\_working\_directory "0-current\_working\_directory") | Write a script that prints the absolute path name of the current working directory.                                                                                                                                                                                             |
| [1-listit](https://github.com/IHansen225/shell/blob/master/basics/1-listit "1-listit")                                                                | Display the contents list of your current directory.                                                                                                                                                                                                                            |
| [10-back](https://github.com/IHansen225/shell/blob/master/basics/10-back "10-back")                                                                   | Write a script that changes the working directory to the user’s home directory.                                                                                                                                                                                                 |
| [11-lists](https://github.com/IHansen225/shell/blob/master/basics/11-lists "11-lists")                                                                | Display current directory contents in a long format                                                                                                                                                                                                                             |
| [12-file\_type](https://github.com/IHansen225/shell/blob/master/basics/12-file\_type "12-file\_type")                                                 | Display current directory contents, including hidden files (starting with .). Use the long format.                                                                                                                                                                              |
| [13-symbolic\_link](https://github.com/IHansen225/shell/blob/master/basics/13-symbolic\_link "13-symbolic\_link")                                     | Display current directory contents.                                                                                                                                                                                                                                             |
| [14-copy\_html](https://github.com/IHansen225/shell/blob/master/basics/14-copy\_html "14-copy\_html")                                                 | Create a script that creates a directory named my\_first\_directory in the /tmp/ directory.                                                                                                                                                                                     |
| [15-lets\_move](https://github.com/IHansen225/shell/blob/master/basics/15-lets\_move "15-lets\_move")                                                 | Move the file betty from /tmp/ to /tmp/my\_first\_directory.                                                                                                                                                                                                                    |
| [16-clean\_emacs](https://github.com/IHansen225/shell/blob/master/basics/16-clean\_emacs "16-clean\_emacs")                                           | Delete the file betty.                                                                                                                                                                                                                                                          |
| [17-tree](https://github.com/IHansen225/shell/blob/master/basics/17-tree "17-tree")                                                                   | Delete the directory my\_first\_directory that is in the /tmp directory.                                                                                                                                                                                                        |
| [2-bring\_me\_home](https://github.com/IHansen225/shell/blob/master/basics/2-bring\_me\_home "2-bring\_me\_home")                                     | Write a script that changes the working directory to the previous one.                                                                                                                                                                                                          |
| [3-listfiles](https://github.com/IHansen225/shell/blob/master/basics/3-listfiles "3-listfiles")                                                       | Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.                               |
| [4-listmorefiles](https://github.com/IHansen225/shell/blob/master/basics/4-listmorefiles "4-listmorefiles")                                           | Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.                                                                                                                                   |
| [5-listfilesdigitonly](https://github.com/IHansen225/shell/blob/master/basics/5-listfilesdigitonly "5-listfilesdigitonly")                            | Create a symbolic link to /bin/ls, named \_\_ls\_\_. The symbolic link should be created in the current working directory.                                                                                                                                                      |
| [6-firstdirectory](https://github.com/IHansen225/shell/blob/master/basics/6-firstdirectory "6-firstdirectory")                                        | Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. |
| [7-movethatfile](https://github.com/IHansen225/shell/blob/master/basics/7-movethatfile "7-movethatfile")                                              | Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.                                                                                                                                                                                |
| [8-firstdelete](https://github.com/IHansen225/shell/blob/master/basics/8-firstdelete "8-firstdelete")                                                 | Create a script that deletes all files in the current working directory that end with the character ~.                                                                                                                                                                          |
| [9-firstdirdeletion](https://github.com/IHansen225/shell/blob/master/basics/9-firstdirdeletion "9-firstdirdeletion")                                  | Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.                                                                                                                                                              |
