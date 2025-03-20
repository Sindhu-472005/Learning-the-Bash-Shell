# Learning-the-Bash-Shell

Shell 

Shell is a command line interface which allow users to interact with operating through entering commands in it. it acts as a intermediate between users and system's kernel, its main work is to process and execute commands.

History of UNIX shells

1. sh -- Bourne shell, which is the original UNIX shell it is very simple      amd fast.

2. csh -- C shell introduced scripting improvements and history features to the commands

3. ksh -- korn shell

4. bash -- Bourne again shell this is a open source extension of sh with enhanced scripting.



Bash shell - Bourne again shell is the default command line for most of the linux distributions. it allow us to execute command or scripts interactivily but one at a time.  

Basic shell Commands

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



















