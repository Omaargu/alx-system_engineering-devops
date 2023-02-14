#!/bin/bash
* alias ls="rm *": Create a script that creates an alias.

    Name: ls
    Value: rm *
* echo hello $USER :Create a script that prints hello user, where user is the current Linux user
* PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
* echo $PATH | tr ":" "\n" | wc -l : Create a script that counts the number of directories in the PATH
* printenv : Create a script that lists environment variables
* set : Create a script that lists all local variables and environment variables, and functions
* BEST="School": Create a script that creates a new local variable
* export BEST="School" : Create a script that creates a new global variable.

    Name: BEST
    Value: School
* echo $((128 + TRUEKNOWLEDGE)) : Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
* echo $(($POWER / $DIVIDE)) : Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

    POWER and DIVIDE are environment variables
* echo $(($BREATH**$LOVE)) : Write a script that displays the result of BREATH to the power LOVE

    BREATH and LOVE are environment variables
    The script should display the result, followed by a new line
* echo $((2#$BINARY)) : binary to decimal
* echo {a..z}{a..z} | tr ' ' '\n' | grep -v 'oo' : reate a script that prints all possible combinations of two letters, except oo.

    Letters are lower cases, from a to z
    One combination per line
    The output should be alpha ordered, starting with aa
    Do not print oo
    Your script file should contain maximum 64 characters
*  
