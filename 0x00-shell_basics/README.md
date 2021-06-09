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
## file /tmp/iamafile
12-file type - a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
## ln -s /bin/ls __ls__
13-symbolic link - a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
## cp -n -u *.html ..
14-copy html - a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
## mv [[:upper:]]* /tmp/u
100-lets-move - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
## rm *~
101-clean emacs - a script that deletes all files in the current working directory that end with the character ~.
## mkdir -p welcome/to/holberton
102-tree - a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory.
