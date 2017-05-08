# Linux-Fun

## Search for packages in the repository 
apt-cache shearch bluefinsh*

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

ll









