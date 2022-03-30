#!/bin/bash
pwd-prints the absolute path name of the current working directory

ls-display the contents list of the current directory

cd ~ -changes working directory to user home directory

ls -l - display current directory contents in a long format

ls -la Display current directory contents, including hidden files in long format

ls -lan Display current directory in long format, with user and group IDs displayed numerically and include hidden files as well

mkdir /tmp/my_first_directory - creates a directory name my_first_directory in the already existing /tmp directory

mv /tmp/betty /tmp/my_first_directory -moves the file betty from tmp folder to my_first_directory folder

rm /tmp/my_first_directory/betty - deletes the file betty

rm -r /tmp/my_first_directory - deletes the directory my_first_directory from the tmp directory

cd -  changes the working directory to the previous one

ls -la . .. /boot - list in long format, including hidden files, the contents of the current directory, its parent directory and the boot directory

file tmp/iamafile - prints the type of the file named iamafile stored in the tmp directory

ln -s /bin/ls __ls__ - create a symbolic link named __ls__ to /bin/ls in the working directory
