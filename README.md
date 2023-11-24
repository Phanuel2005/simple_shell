# Simple shell 0.1
Write a UNIX command line interpreter.

Usage: simple-shell

Your Shell should:

Display a prompt and wait for the user to type a command. A command line always ends with a new line.

The prompt is displayed again each time a command has been executed.

The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.

The command lines are made only of one word. No arguments will be passed to programs.

If an executable cannot be found, print an error message and display the prompt again.

Handle errors.

You have to handle the “end of file” condition (Ctrl+D)

You don’t have to:

use the PATH

implement built-ins

handle special characters : ", ', , \, *, &, #

be able to move the cursor

handle commands with arguments
