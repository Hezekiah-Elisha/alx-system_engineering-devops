## su betty
0-iam betty - a script that switches the current user to the user betty.

* You should use exactly 8 characters for your command (+1 character for the new line)
* You can assume that the user betty will exist when we will run your script
## whoami
1. Who am I - a script that prints the effective username of the current user.
## groups
2-groups - a script that prints all the groups the current user is part of.
## chown betty hello
3-new owner - a script that changes the owner of the file hello to the user betty.
## touch hello
4-empty - a script that creates an empty file called hello.
## chmod u+x hello
5-execute - a script that adds execute permission to the owner of the file hello.
## chmod 0+r, g+x, u+x hello
6-multiple permissions - a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
## chmod ug0-x hello
7-everybody - Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

* The file hello will be in the working directory
* You are not allowed to use commas for this script
## chmod 007 Hello
8-James Bond - Write a script that sets the permission to the file hello as follows:

* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions
## chmod 753 hello
9-John Doe - a script that sets the mode of the file hello:
* ```-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```
## chmod --refference=olleh hello
10-mirror_permissions - a  script that sets the mode of the file hello the same as olleh’s mode.

* The file hello will be in the working directory
* The file olleh will be in the working directory
## chmod -R ugo+X ./*
11-directories_permissions - a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
## mkdir -m 751 dir holberton
12-directory_permissions - a script that creates a directory called dir_holberton with permissions 751 in the working directory.
## chgrp holberton hello
13-change_group - a script that changes the group owner to holberton for the file hello
## chown -hR betty:holberton .
100-change_owner_and_group - a script that changes the owner to betty and the group owner to holberton for all the files and directories in the working directory.
## chown -h betty:holberton _hello
101-symbolic_link_permissions - Write a script that changes the owner and the group owner of _hello to betty and holberton respectively.

* The file _hello is in the working directory
* The file _hello is a symbolic link
