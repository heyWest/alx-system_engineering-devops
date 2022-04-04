
su - betty Switches the current user to the user betty

whoami - Prints the effective username of  the current user

groups - Prints all the groups the current user is part of

sudo chown betty hello = changes the owner of the file hello to the user betty

touch hello - creates an empty file called hello

chmod 100 hello - adds execute permission to the owner of the file hello

chmod 114 hello - adds execute permission to the owner and the group owner and read permission to the other users, to the file hello

chmod 111 hello - adds execution permission to the owner, the group owner and the other users, to the file hello

chmod 007 hello - set the permissions to the file hello with no permission to the owner and group owner but all permissions to the other users

chmod 753 hello - set all permission to owner, read and execute permissions to group owner and then write and execute permissions to the other users

chmod --reference=olleh hello - sets the mode of the file hello the same as the file olleh

mkdir -m 751 my_dir -creates a directory called my_dir with permissions 751 in the working directory

chgrp school hello - changes the group owner to school for the file hello
