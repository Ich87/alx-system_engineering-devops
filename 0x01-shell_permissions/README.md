#!/bin/bash
about permissions
1. su betty: to switch the current user to betty
2. whoami: to print effective username of current user
3. groups: to print all the groups the current user is part of
5. chown: use to change owner of file
6. touch: to write and empty file eg touch hello
7. chmod u+x: to add execution permission to a file
8. chmod ug+x,o+r; to add execution permission to user and group, and only read permission to other users
9. chmod ugo+x: to add executable permission to the user, group and other users
10. chmod 007: owner no permission, group no permission, other user  all permission
11. chmod 753: all permission to owner,read and execute permission to group, execute permission to other users
12. chmod --reference=olleh hello: mirrow command
13. chmod -R +X .: give execution permission to all subdirectories of the current directory for all users
14. mkdir -m 751: create a directory and give it permission 751
