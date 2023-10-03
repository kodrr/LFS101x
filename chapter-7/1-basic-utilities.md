Basic
cd: change directory, if no option it will change directory to home root
ls
rmdir
rm -r
exit
login
mkdir
touch
cat: used to type out a file (or combine files).
head: used to show the first few lines of a file.
tail: used to show the last few lines of a file.
man: used to view documentation.
|: pipe symbol, used to have one program take as input the output of another.
grep: print lines that match patterns
echo: display text int he terminal
    ex. echo -e "Line 1\nLine 2\tIndented"
        my_variable="World"
        echo "Hello, $my_variable!"
ssh: remote login client

shell prompt 3 basic elements
command
option
arguments

Creating New user
sudo adduser <newuser>
sudo usermod -aG sudo <newuser>
su - <newuser>

Removing user
sudo deluser --remove-home <username>
sudo deluser <username> //keep their home directory and files

Rebooting and Shutting Down
sudo shutdown -h 10:00 "Shutting down for scheduled maintenance."  //for system booted in systemd

Locating Applications
which diff
whereis diff
man: manual

Changing Directories
pwd
cd ~ home directory
cd / root directory
cd .. change to parent directory
cd - previous working directory (switch between)

Absolute and Relative Paths
Absolute: cd /usr/bin
Relative: cd ../../usr/bin //relative to where you are

Filesystem
tree -d //sudo apt install tree
cd /
ls 
ls -la //list long all - including hidden files and directories whose name start with .
ctrl l, clear
df: disk file
df -h : human readable

Hard Links
ln file1 file2
ls -li file1 file2 // -i prints the inode in first column, a unique quantity for each file object in this case file2 is same with file1

Soft (Symbolic) Links
touch file1
ln -s file1 file3
ls -li file1 file3

Directory History
pushd
popd
dirs