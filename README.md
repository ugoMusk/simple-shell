
# Simple shell Project

A simple unix command line interpreter

## Table of content

Any additional information goes here

What is the shell?

About this project

Essential Functionalities of the Simple Shell

File description

List of allowed functions and system calls for this project

USAGE

Example of Usage

Bugs

TEAM
## What is Shell

The shell is a program that takes commands from the keyboard via the terminal, and gives them to the operating system to perform.
To better understand how the shell actually works, you can read our [Article].

## About this project

This project is a simple version of the linux shell made for [ALX SOFTWARE ENGINERRING] taking part of the "Simple Shell - Linux and Unix system programming" Project.
It is created using the C programming Language and it can do many functionalities that a real shell does.
## Essential Functionalities of the Simple Shell:

- Displays a prompt "#cisfun$ " and waits for user input.
- Runs all commands of type "executable program" (ls and /bin/ls).
- Runs the following build_in commands: exit, env, setenv and unsetenv.
- Handles commands with arguments.
- Handles the PATH global variable.
- Handles The EOF (End Of File) condition.
- Handles the Ctrl + C signal -> It doesn't exit the shell

## Files description

This is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program is been written entirely in C as a milestone project for Alx School.

## List of allowed functions and system calls for this project

- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write )



## Usage

Clone our repository using this command, (you need to have git installed on your machine first)

```bash
  git clone https://github.com/ugoMusk/simple_shell
```

Change directory to simple_shell:

```bash
  cd simple_shell
```

Change directory to simple_shell:

```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o ugosh
```

 Run the shell

```bash
  ./ugosh
```

EXITING THE shell: when you want to exit the shell, you can ue one of the following methods

- Type command "exit"
```bash
exit
```
- Press Ctrl + D




## Example of usage


```bash
After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.
```
    
## Bugs

No none bugs
## Authors

- [@Itguru2022](https://www.github.com/Itguru2022)

- [@ugoMusk](https://www.github.com/ugoMusk)

