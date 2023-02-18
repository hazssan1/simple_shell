# simple_shell
A simple UNIX command line interpreter that replicates the functionalities of the simple shell.This program was written entirely in C as a requirement and milestone project for ALX Africa Software Engineering program.

A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts

# Installation

Clone this repository into your working directory. Files should be compiled with the gcc in this manner: ```gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh```

# Usage

After compilation, the shell can run either in interactive or non-interactive mode

### Interactive mode

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

```example
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```

### Non-Interactive mode

In non-interactive mode, echo your desired command and pipe it into the program like this:
```echo "ls" | ./shell```

In non-interactive mode, the program will exit after finishing your desired command(s).
