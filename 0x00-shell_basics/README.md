#!/bin/bash
My second readme
pwd prints the absolute path name of the current working directory
ls lists the content of the current working directory
cd ~ changes working directory to home directory
ls -l Display current directory contents in a long format
ls -la Displays current directory contents including hidden files in a long format
ls -na Display current directory contents in a Long format with user and group IDs displayed numerically And hidden files
mkdir -p /tmp/my_first_directory: Creates a script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory Moves the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory: Delete the file betty.The file betty is in /tmp/my_first_directory
rm -r /tmp/my_first_directory:Delete the directory my_first_directory that is in the /tmp directory.
cd -: changes the working directory to the previous one
ls -al . .. /boot: lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile:  prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s bin/ls __ls__:Creates a symbolic link to /bin/ls, named __ls__.
cp -rua *.html ../:Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u: moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~: deletes all files in the current working directory that end with the character ~
mkdir -p welcome/to/school:creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
ls -map:Write a command that lists all the files and directories of the current directory, separated by commas (,)
