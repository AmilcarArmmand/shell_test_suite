# Simple Shell, Checks

There will be no checks released before the deadline. We **strongly** encourage the whole class to work together and create a suite of checks covering both regular tests and edged cases for each task.

Here is an example on how to check your shell.
Fork this repo and add more checks to help you and the rest of the class build the best simple shell possible.

## Style Guide
https://google.github.io/styleguide/shellguide.html

## Configuration

Open the file `config` and update the variable `SHELL` with your shell. Remove the hash mark (#) from beginning of the SHELL that you want to test.

## Test Driven Development

[What is Test Driven Development(TDD)?](https://www.guru99.com/test-driven-development.html)

## Run

Usage `./check_simple_shell.bash`
This will run all the tests and create output log files and save them to the /logs directory.

## Tests :computer:

### [01_simple_shell_0.1](./01_simple_shell_0.1) (task 3)

* [bin_ls](./01_simple_shell_0.1/bin_ls) - Test simple command /bin/ls.
* [bin_ls_extra_line](./01_simple_shell_0.1/bin_ls_extra_line) - Test bin/ls twice with a blank lin bwteen.
* [bin_ls_spaces ](./01_simple_shell_0.1/bin_ls_spaces) - Run /bin/ls many times, with a lot of spaces everywhere.
* [bin_ls_x3](./01_simple_shell_0.1/bin_ls_x3) - Run /bin/ls 3 times.
* [medium_size_input](./01_simple_shell_0.1/medium_size_input) - Check if a medium size command line does not break the shell.]

### [02_simple_shell_0.1.1](./02_simple_shell_0.1.1) (task 4 #advanced)

* [no_getline](./02_simple_shell_0.1.1/no_getline) - Check if the getline (man 3 getline) function was used by using ltrace.

### [03_simple_shell_0.2](./03_simple_shell_0.2) (task 5)

* [bin_ls_la_dir](./03_simple_shell_0.2/bin_ls_la_dir) - Run ls with arguments
* [print_error]d/shell_test_suite/blob/master/06_simpl - Print error message if command is not found

### [04_simple_shell_0.2.1](./04_simple_shell_0.2.1) (task 6 #advanced)

* [no_strtok](./04_simple_shell_0.2.1/no_strtok) - Check if the strtok (man 3 strtok) function was used by using ltrace.

### [05_simple_shell_0.3](./05_simple_shell_0.3) (task 7)

* [bin_ls_empty_path](./05_simple_shell_0.3/bin_ls_empty_path) - Empty the PATH and check if /bin/ls still works.
* [ls](./05_simple_shell_0.3/ls) - Test with ls to check if the shell can find ls in the PATH.
* [ls_bin_ls](./05_simple_shell_0.3/ls_bin_ls) - Run a mix of ls and /bin/ls many times.
* [ls_bin_ls_spaces](./05_simple_shell_0.3/ls_bin_ls_spaces) - Run a mix of ls and /bin/ls many times, with spaces.
* [ls_current_path](./05_simple_shell_0.3/ls_current_path) - Check that the PATH is checked in the right order.
* [ls_empty_path](./05_simple_shell_0.3/ls_empty_path) - Check also that an error message is printed to the user.
* [ls_spaces](./05_simple_shell_0.3/ls_spaces) - Run ls with spaces everywhere.
* [ls_l](./03_simple_shell_0.2/ls_l) - Find command in the PATH and run it with arguments (ls -l)
* [ls_la](./03_simple_shell_0.2/ls_la) - Find command in the PATH and run it with arguments (ls -la)

### [06_simple_shell_0.4](./06_simple_shell_0.4) (task 8)

* [exit](./06_simple_shell_0.4/exit) - Check the exit built-in with no arguments. :wrench:

### [07_simple_shell_0.4.1](./07_simple_shell_0.4.1) (task 9 #advanced)

* exit_status - Check the exit built-in with an integer used to exit the shell. :wrench:

### [08_simple_shell_0.4.2](./08_simple_shell_0.4.2) (task 10 #advanced)

* ctrl_c - Handle Ctrl+C, the shell should not quit when user inputs ^C. :wrench:

### [09_simple_shell_1.0+](./09_simple_shell_1.0) (tasks 11, 12, 13, 14, 15, 16, 17, 18, 19, and 20)

* env built-in  :wrench:
* Implement the setenv and unsetenv built-in commands  :wrench:
* Implement the cd built-in command :wrench:
* Handle the commands separator ;   :wrench:
* Handle the && and || shell logical operators  :wrench:
* Implement the alias built-in command :wrench:
* Handle variables replacement, $? and $$ :wrench:
* Handle comments (#) :wrench:
* Implement the help built-in :wrench:
* Implement the history built-in, without any argument :wrench:
