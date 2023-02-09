#!/bin/bash
su user : change between users
whoami : print username of current user
groups : shows all the groups the current user is art of
sudo chown : change a file to a new user
touch : create empty file
chmod 744:gives owner permission to execute
chmod 754: execute permission to the owner and the group owner, and read permission to other
chmod ugo+x:adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello:Write a script that sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
chmod 753 hello : a script that sets the mode of the file hello to this: rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod --reference : Write a script that sets the mode of the file hello the same as olleh’s mode.

    The file hello will be in the working directory
    The file olleh will be in the working directory
 
