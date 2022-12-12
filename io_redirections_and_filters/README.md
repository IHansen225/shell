## Project: Shell, I/O Redirections and filters
### Description:
Input/output manipulation scripts.
### Learning objectives:

#### Shell, I/O Redirection

-   What do the commands `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr` do
-   How to redirect standard output to a file
-   How to get standard input from a file instead of the keyboard
-   How to send the output from one program to the input of another program
-   How to combine commands and filters with redirections

#### Special Characters

-   What are special characters
-   Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them

### Tasks:
| File                                                                                                                         | Description                                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [0-hello\_world](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/0-hello_world)                  | Write a script that prints “Hello, World”, followed by a new line to the standard output.                                                                              |
| [1-confused\_smiley](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/1-confused_smiley)          | Write a script that displays a confused smiley "(Ôo)'                                                                                                                  |
| [10-no\_more\_js](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/10-no_more_js)                 | Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.         |
| [11-directories](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/11-directories)                 | Write a script that counts the number of directories and sub-directories in the current directory.                                                                     |
| [12-newest\_files](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/12-newest_files)              | Create a script that displays the 10 newest files in the current directory.                                                                                            |
| [13-unique](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/13-unique)                           | Create a script that takes a list of words as input and prints only words that appear exactly once.                                                                    |
| [14-findthatword](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/14-findthatword)               | Display lines containing the pattern “root” from the file /etc/passwd                                                                                                  |
| [15-countthatword](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/15-countthatword)             | Display the number of lines that contain the pattern “bin” in the file /etc/passwd                                                                                     |
| [16-whatsnext](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/16-whatsnext)                     | Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.                                                                            |
| [17-hidethisword](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/17-hidethisword)               | Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.                                                                                   |
| [18-letteronly](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/18-letteronly)                   | Display all lines of the file /etc/ssh/sshd\_config starting with a letter.                                                                                            |
| [19-AZ](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/19-AZ)                                   | Replace all characters A and c from input to Z and e respectively.                                                                                                     |
| [2-hellofile](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/2-hellofile)                       | Display the content of the /etc/passwd file.                                                                                                                           |
| [20-hiago](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/20-hiago)                             | Create a script that removes all letters c and C from input.                                                                                                           |
| [21-reverse](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/21-reverse)                         | Write a script that reverse its input.                                                                                                                                 |
| [22-users\_and\_homes](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/22-users_and_homes)       | Write a script that displays all users and their home directories, sorted by users.                                                                                    |
| [23-empty\_casks](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/23-empty_casks)                | Write a command that finds all empty files and directories in the current directory and all sub-directories.                                                           |
| [24-gifs](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/24-gifs)                               | Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.                                                    |
| [25-acrostic](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/25-acrostic)                       | Create a script that decodes acrostics that use the first letter of each line.                                                                                         |
| [26-the\_biggest\_fan](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/26-the_biggest_fan)       | Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.                              |
| [3-twofiles](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/3-twofiles)                         | Display the content of /etc/passwd and /etc/hosts                                                                                                                      |
| [4-lastlines](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/4-lastlines)                       | Display the last 10 lines of /etc/passwd                                                                                                                               |
| [5-firstlines](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/5-firstlines)                     | Display the first 10 lines of /etc/passwd                                                                                                                              |
| [6-third\_line](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/6-third_line)                    | Write a script that displays the third line of the file iacta.                                                                                                         |
| [7-file](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/7-file)                                 | Write a shell script that creates a file named exactly \\\*\\\\'"Best School"\\'\\\\\*$\\?\\\*\\\*\\\*\\\*\\\*:) containing the text Best School ending by a new line. |
| [8-cwd\_state](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/8-cwd_state)                      | Write a script that writes into the file ls\_cwd\_content the result of the command ls -la.                                                                            |
| [9-duplicate\_last\_line](https://github.com/IHansen225/shell/blob/master/io_redirections_and_filters/9-duplicate_last_line) | Write a script that duplicates the last line of the file iacta                                                                                                         |
