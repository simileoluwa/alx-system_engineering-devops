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

#9. Write a script that prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables.
used echo $((POWER/DIVIDE))

#10. Write a script that displays the result of BREATH to the power LOVE
used echo $((BREATH**LOVE))

#11. Write a script that converts a number from base 2 to base 10.
echo $((2#$BINARY))

#12. Create a script that prints all possible combinations of two letters, except oo. Letters are lower cases, from a to z One combination per line The output should be alpha ordered, starting with aa Do not print oo Your script file should contain maximum 64 characters
used printf %s'\n' {a..z}{a..z} | grep -v "oo"

#13.Script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.
printf %0.2f'\n' $NUM

#14. Write a script that converts a number from base 10 to base 16.
printf "%x\n" $DECIMAL 

#15. Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
used tr 'A-Za-z' 'N-ZA-Mn-za-m'

#16. 



