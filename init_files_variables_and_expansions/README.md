## Project: # Shell, init files, variables and expansions
### Description:
Global/local variables managing and Linux init file operation scripts
### Learning objectives:
#### General

-   What happens when you type `$ ls -l *.txt`

#### Shell Initialization Files

-   What are the `/etc/profile` file and the `/etc/profile.d` directory
-   What is the `~/.bashrc` file

#### Variables

-   What is the difference between a local and a global variable
-   What is a reserved variable
-   How to create, update and delete shell variables
-   What are the roles of the following reserved variables: HOME, PATH, PS1
-   What are special parameters
-   What is the special parameter `$?`?

#### Expansions

-   What is expansion and how to use them
-   What is the difference between single and double quotes and how to use them properly
-   How to do command substitution with `$()` and backticks

#### Shell Arithmetic

-   How to perform arithmetic operations with the shell

#### The `alias` Command

-   How to create an alias
-   How to list aliases
-   How to temporarily disable an alias
### Tasks:
| File                                                                                                                                         | Description                                                                                                                                           |
| -------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [0-alias](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/0-alias)                                       | Create a script that creates an alias.                                                                                                                |
| [1-hello\_you](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/1-hello_you)                              | Create a script that prints hello user, where user is the current Linux user.                                                                         |
| [10-love\_exponent\_breath](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/10-love_exponent_breath)     | Write a script that displays the result of BREATH to the power LOVE                                                                                   |
| [11-binary\_to\_decimal](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/11-binary_to_decimal)           | Write a script that converts a number from base 2 to base 10.                                                                                         |
| [12-combinations](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/12-combinations)                       | Create a script that prints all possible combinations of two letters, except oo.                                                                      |
| [13-print\_float](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/13-print_float)                        | Write a script that prints a number with two decimal places, followed by a new line.                                                                  |
| [14-decimal\_to\_hexadecimal](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/14-decimal_to_hexadecimal) | Write a script that converts a number from base 10 to base 16.                                                                                        |
| [15-rot13](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/15-rot13)                                     | Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.                                                                |
| [16-odd](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/16-odd)                                         | Write a script that prints every other line from the input, starting with the first line.                                                             |
| [17-water\_and\_stir](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/17-water_and_stir)                 | Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.                              |
| [2-path](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/2-path)                                         | Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.                                        |
| [3-paths](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/3-paths)                                       | Create a script that counts the number of directories in the PATH.                                                                                    |
| [4-global\_variables](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/4-global_variables)                | Create a script that lists environment variables.                                                                                                     |
| [5-local\_variables](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/5-local_variables)                  | Create a script that lists all local variables and environment variables, and functions.                                                              |
| [6-create\_local\_variable](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/6-create_local_variable)     | Create a script that creates a new local variable.                                                                                                    |
| [7-create\_global\_variable](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/7-create_global_variable)   | Create a script that creates a new global variable.                                                                                                   |
| [8-true\_knowledge](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/8-true_knowledge)                    | Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line. |
| [9-divide\_and\_rule](https://github.com/IHansen225/shell/blob/master/init_files_variables_and_expansions/9-divide_and_rule)                 | Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.                                                             |
