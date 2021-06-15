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
## ls -ls | grep -c ^d 
11-directories - a script that counts the number of directories and sub-directories in the current directory.

* The current and parent directories should not be taken into account
* Hidden directories should be counted
## ls -t | head
12-newest_files - a script that displays the 10 newest files in the current directory.

Requirements:

* One file per line
* Sorted from the newest to the oldest
## sort list | uniq -u
13-unique - a script that takes a list of words as input and prints only words that appear exactly once.

* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted
## grep -e "root" /etc/passwd
14-findthatword - diplayss lines containing the pattern "root" from the file /etc/passwd
## grep -c "bin" /etc/passwd
15-countthatword - Display the number of lines that contain the pattern “bin” in the file /etc/passwd
## grep -e "root" /etc/passwd | grep -A 3 "root"
16-whatsnext - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
## grep -v "bin" /etc/passwd
17-hidethisword - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
## grep -e "^[[:alpha:]]" /etc/ssh/sshd_config
Displays all lines of the file /etc/ssh/sshd_config starting with a letter.

* include capital letters as well
## tr 'Ac' 'Ze'
19-AZ - Replace all characters A and c from input to Z and e respectively.
## tr -d "cC"
20-hiago - Create a script that removes all letters c and C from input.
## rev
21- esreveR - a script that reverses its input
## cut -d":" --fields=1,6 /etc/passwd | sort
22-users_and_homes = Write a script that displays all users and their home directories, sorted by users.

* Based on the the /etc/passwd file
## find -empty -printf "%f\n"
100-empty_casks -  a command that finds all empty files and directories in the current directory and all sub-directories.

* Only the names of the files and directories should be displayed (not the entire path)
* Hidden files should be listed
* One file name per line
* The listing should end with a new line
* You are not allowed to use basename, grep, egrep, fgrep or rgrep
## find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f
101-gifs -  a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

* Hidden files should be listed
* Only regular files (not directories) should be listed
* The names of the files should be displayed without their extensions
* The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
* One file name per line
* The listing should end with a new line
* You are not allowed to use basename, grep, egrep, fgrep or rgrep
