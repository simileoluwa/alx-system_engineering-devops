#0x03-shell_variables_expansions
#0. Create a script that creates an alias. Name: ls Value: rm *
It should be alias ls="rm *"

#1. Create a script that prints hello user, where user is the current Linux user.
echo "hello $USER"

#2.Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
using echo "$PATH:/action" 

#3.Create a script that counts the number of directories in the PATH.
using echo $PATH | tr ':' '\n' | wc -l

#4. Create a script that lists environment variables.
using printenv

#5. Create a script that lists all local variables and environment variables, and functions.
using "set"

#6. Create a script that creates a new local variable.
#Name: BEST and Value: School
Using BEST="School"

#7. Create a script that creates a global variable called BEST and Value:School
using export BEST="School"

#8. Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
used echo $((TRUEKNOWLEDGE + 128))
