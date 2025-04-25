# Simple Shell Project

## Project Overview
The **Simple Shell** project is a custom implementation of a Unix shell. It replicates the behavior of `/bin/sh` and allows users to execute commands interactively or non-interactively. This project is part of the curriculum at Holberton School and aims to strengthen the understanding of system calls, memory management, and process handling.

### Purpose
The purpose of this project is to:
- Understand how a Unix shell works internally.
- Gain hands-on experience with system calls, process management, and I/O redirection.
- Improve programming skills in C by building a functional shell.

### Main Features
1. Displays a prompt and waits for user input.
2. Executes commands with or without arguments.
3. Resolves commands using the `PATH` environment variable.
4. Handles errors gracefully and supports `Ctrl+D` (EOF).
5. Implements built-in commands like `exit` and `env`.

### Intended Audience
This project is designed for:
- Students and professionals interested in system programming.
- Individuals seeking to deepen their knowledge of Unix-like operating systems.
- Developers exploring how command-line interfaces work.


---


### Compilation Instructions
To compile the shell, use:
'gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh' on Ubuntu 20.04 LTS.

## Language
The creation of the Simple Shell project is written in C and adheres to the GNU89 standard.

## Contributors
This project was completed by:

**Gustavo Guevara:** [GitHub Profile](https://github.com/GGGtrainer)
