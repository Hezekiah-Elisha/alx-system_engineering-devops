# BASH commands
## pwd
0-current working directory - The script in this directory prints the absolute path name of the current working directory.
## ls
1-listit -displays the content list of your current directory.
## cd
2-bring me home - changes working directory to the user's home directory.
## ls -l
3-listfiles - Displays current directory contents in a long format
## ls -l -a
4-listmorefiles - Displays current directory contents, including hidden files (starting with .). Use the long format.
## ls -lna
5-listfilesdigitonly - Display current directory contents.

* Long format
* with user and group IDs displayed numerically
* And hidden files (starting with .)
## mkdir /tmp/holberton/
6-firstdirectory - Creates a script that creates a directory named holberton in the /tmp/ directory.
## mv /tmp/betty /tmp/holberton/
7-movethatfile - Moves the file betty from /tmp/ to /tmp/holberton.
## rm /tmp/holberton/betty
8-firstdelete - Delete the file betty.

* The file betty is in /tmp/holberton
## rmdir /tmp/holberton
9-firstdirdeletion - Deletes the directory holberton that is in the /tmp directory.
## cd -
10-back - a script that changes the working directory to the previous one.
## ls -l -a . .. /boot
11-lists - a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
