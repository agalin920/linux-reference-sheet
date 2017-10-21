# LinuxReferenceGuide
A small reference guide to all the Linux commands I've learned

cd -optional file directory- (current directory) 
cd .. (parent directory) 
cd ~  (home directory) 
cd -  (previous directory)

pwd print working directory

ls -optional file directory-(list directories)
ls -l (more detailed list)
ls- a (shows hidden directories (.file))

touch -file creation destination-(creates a file)

file (shows file type)

cat (opens the file in the terminal)

history(shows the history of commands)

clear (clears the terminal)

cp filename -file copy destination- (copies a file)
cp -r  directory/ -file copy destination-(copies a whole directory)

mv oldfile newfile (renames file)
mv file -file move directory-(moves a file to a directory; can move more than one at a time)
mv -b (backups the file before a move or rename)

mkdir <directory name> (makes a directory)
rmdir <directory name> (removes directory)
rm -r <directory name> (delete directory and its contents)

whatis <command> (shows the simple explination of the command)

xkill (kills the window you click on)

To fix harddrive

sudo ntfsfix /dev/sdb1

Text Navigation:

CTRL-A : Go to beggining of line
CTRL-E : Go to end of line
CTRL-R : History search
CTRL-C : Keyboard Interrupt

# :       Bash comment

Connect to IRC
/server server
/join channel

Install Deb package

sudo dpkg -i package


//SORT a file
sort <file to be sorted>
//Sort file and save
sort <file to be sorted> >> <New file name>

//Grep search words in file
grep(golbal regular expression print)
grep <Word to search> <file to be searched>
grep -i <Case sensitive word to search> <file to be searched>

//Change bash profile
nano ~/.bash_profile
(write commands in it)>echo "Hello Terminal User"
//Usually done for alias (alias pd="pwd")
(save it and apply)>   source ~/.bash_profile

//Git
git init (Initializ git in the folder)
git status (Status of the git)
git add <filename> (Add the file that is in the folder to the git)
git diff <filename> (Lists and colors the differences/changes in a file)
git commit -m <message for commit>(Permanently stores changes frin the staging area)
git log(chronological commits)


//How-To reboot your system if everything crashes

Ctrl+Alt+F2
Login with credentials
type reboot

//How to install python requirements.txt
sudo pip install -r requirements.txt
