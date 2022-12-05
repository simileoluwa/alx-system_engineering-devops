#this is the readme file for this current project

#0. for Hello world
The echo command is used to print "Hello, World" and double quotes with space inside to show new line. Code used is echo -e "Hello, World\n"

#1. confused smiley
I added a confused smiley using echo -e command to print it out including a new line using "echo -e "/"(O.o)'"

#2. I was told to print the /etc/passwd screen
I used cat /etc/passwd to display content

#3.A script to Display the content of /etc/passwd and /etc/hosts
using cat to display the content of "cat /etc/passwd /etc/hosts" 

#4 Display the last 10 lines of /etc/passwd
Using tail /etc/passwd

#5. Display the first 10 lines of /etc/passwd
Using head /etc/passwd  

#6. A script to display the 3rd line of a file
A script that displays the third line of the file iacta.
The code was "head -n 3 iacta | tail -n 1

#7. Write a shell script that creates a file named exactly \*\\'"Best School"\'\#\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
All i did was to spend almost 1 hour on it trying to escape all the alphanumeric and wildcard symbols

#8. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
Using ls -la > ls_cwd_content

#9. script that duplicates the last line of the file iacta
I appended the result to the file using "tail -n 1 >> iacta"
