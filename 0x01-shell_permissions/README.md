#!/bin/bash
about permissions
su betty: to switch the current user to betty
whoami: to print effective username of current user
groups: to print all the groups the current user is part of
chown: use to change owner of file
touch: to write and empty file eg touch hello
chmod u+x: to add execution permission to a file
chmod ug+x,o+r; to add execution permission to user and group, and only read permission to other users
chmod ugo+x: to add executable permission to the user, group and other users
chmod 007: owner no permission, group no permission, other user  all permission
chmod 753: all permission to owner,read and execute permission to group, execute permission to other users
chmode --reference=olleh hello: mirrow command
