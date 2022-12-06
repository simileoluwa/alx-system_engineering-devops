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
