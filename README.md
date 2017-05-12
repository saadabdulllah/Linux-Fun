# Linux-Fun

## Search for packages in the repository 
apt-cache search bluefinsh*

## look for the package that already installed or not 
apt-cache policy bluefish

## Install package form command line 
sudo dpkg -i ./Downlaods/packagename.deb

## upgrade the kernel 
sudo apt-get upgrade

## File permission 
Create a file with no permission to regular user
$ sudo vim file.txt

## Change the ownership of a file
$ sudo chown user:group file.txt

## Change the permission of a file 
$ sudo chmod 664 file.txt

## Change the ownership forever for a specific group 
$ sudo chmod saad:saad file.txt

## delete a single file 
$ rm file.txt

## Create a directory
$ sudo mkdir Mydir

## TO Change the ownership for a directory as long as everything inside 
$ sudu chown -R saad:saad ./Mydir
note: attribute -R means resursive 

## Create a new file 
$ touch file.txt

## Remove a directory
$ rmdir Mydir
or force remove 
$ rm -rf Mydir

## copy file 
$ cp ./mydir/file.txt ./anotherdir/file.txt
note: it is possible to remane the file while copying to another directory

## move a file 
$ mv ./mydir/file.txt ./anotherdir

## switch user
$ su

## Remove a program 
$ sudo apt-et install remove 

----

# Find Commad uses 

## To find all file in a same extention using find command 
find is case sensative
    find [directory][-type][f for file][-name] ["" and what to look for]
$ find . -type f -name "*.java" 

to ignote case sensitive use [-iname] insate of [-name]

$ find . -type f -iname "file*"

## find files with certain permission 
$ find . -type f -perm 0664

## find with file size 
$ find . -size +1m


## find file  with not operator, find file that are not .php
$ find . -type f -not -iname "*.php"




















