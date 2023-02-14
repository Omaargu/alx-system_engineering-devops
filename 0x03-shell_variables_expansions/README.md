#!/bin/bash
* alias ls="rm *": Create a script that creates an alias.

    Name: ls
    Value: rm *
* echo hello $USER :Create a script that prints hello user, where user is the current Linux user
* PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
* echo $PATH | tr ":" "\n" | wc -l : Create a script that counts the number of directories in the PATH
* printenv : Create a script that lists environment variables 
