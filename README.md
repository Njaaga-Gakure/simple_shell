# Simple Shell README

## Synopsis

This project entails a simple implementation of the LINUX shell that has the same output as sh

## Description

This Simple Shell can take arguments from standard input i.e keyboard, tokenize the commands if more that one argument is provided by the user and runs the command if it exists. After the command is run, the shell asks the user for input again infinitely unless the exit command is run. If the command entered does not exist, an error massages is outputted to the standard error. 
Your shell will be compiled using gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
