# Learning-the-Bash-Shell
Basic shell Commands

Bash shell - Bourne again shell is the default command line for most of the linux distributions. it allow us to execute command or scripts interactivily but one at a time.  


history of commands

Bash stores all our previous commands, we can access it by using:

**history** --- shows the list of our recent commands

**!number** - execute a command from our command history by its number

**!!** - repeats the last command



**Directory management**

Command **mv file1.txt Documents/** moves a file named file1.txt to the documents directory 

Command **u+rwx, g+rx, o+rx script.sh** gives full permissiond to the owner and read+execute to group and others

**grep error logfile.txt** finds and prints lines containing error in logfile.txt

**wc-l** counts the number of lines in a file

**wc -w** Counts the number of words in a file.

**wc -m** Counts the number of characters in a file

**wc -c** → Counts the number of bytes in a file

**ls** list files in a directory 

**ls-l** lists all files with detailed information, permission and size etc.

**ls -s** Shows the file sizes in blocks.

**ls -a** →Lists all files, including hidden ones.

**ls -h** Displays file sizes in a human-readable format

**cd/path** changes the directory

**cd/home** changes the directory to home

**pwd** shows the current directory path

**mkdir dir** creates new directory

**rm file** removes file


**Networks**

**ifconfig** shows network interfaces

**ip a** shows IP addresses


**Process Management**

**ps aux** lists running processes

**top** shows system resource usuage 



















