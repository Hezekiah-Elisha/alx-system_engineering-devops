# Shell, I/O Redirection
## echo "Hello, World"
0-Hello world - a script that prints “Hello, World”, followed by a new line to the standard output.
## echo "\"(Oo)'"
1-confused smiley - a script that displays a confused smiley "(Ôo)'
## cat /etc/passwd
2-hellofile - Displays the content of the /etc/passwd file
## cat /etc/passwd /etc/hosts
3-twofiles - Displays the content of /etc/passwd and /etc/hosts
## tail -n 10 /etc/passwd
4-lastlines - displays the last 10 lines of /etc/passwd
## head -n 10 /etc/passwd
5-firstlines - displays the first 10 lines of /etc/passwd
## head -n 3 iacta | tail -n 1
6-third line - Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory

* You’re not allowed to use sed
## echo "Holberton School" >  ''\*\\'\"Holberton School\"\'\\*\$\?\*\*\*\*\*\:\)''
7-file - a shell script that creates a file named exactly \*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:) containing the text Holberton School ending by a new line.
## ls -la > 'ls_cwd_content'
8-cwd state - a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
## tail -n 1 iacta >> iacta
9-duplicate_last_line - a script that duplicates the last line of the file iacta

* The file iacta will be in the working directory
## find -name "*.js" -type f -delete 
10-no_more_js - a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
## 
1 -ls | grep -c ^d -directories - a script that counts the number of directories and sub-directories in the current directory.

* The current and parent directories should not be taken into account
* Hidden directories should be counted
