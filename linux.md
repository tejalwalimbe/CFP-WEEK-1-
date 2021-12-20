# Linux

## Linux Commands
As every deployment environment is Linux based, it is very important to learn and become proficient with Linux commands for both deployments and debugging issues.

Hint : The easy way to learn, You will get all documentation and syntax of command and options.
These are two below options to get all things.
~~~
$ man <command>
$ <command> --help
~~~

## File System Management Command 

### e2fsck : 
   e2fsck is used to examine ext2/ext3/ext4 filesystems for errors and fsck checks and can optionally repair a Linux filesystem; it is basically a front-end for a range of filesystem checkers (fsck. fstype for example fsck. ext3, fsck. sfx etc) offered under Linux. 
 
Attention: Do not run e2fsck or fsck on mounted filesystems, always unmount a partition first before you can run these tools on it, as shown below.
For more information [Click Here](https://www.tecmint.com/manage-ext2-ext3-and-ext4-health-in-linux)

# Below is the list of most used commands.

## File Management Commands

| Command  | Description |
| ------------- | ------------- |
| chgrp  | Changes a file's/directory group.  |
| chmod  | Changes a file's/directory permissions.  |
| chown  | Changes a file's/directory user ownership.  |
| cp  | Copies a file  |
| df  | Displays disk usage statistics  |
| du  | Displays directory space usage  |
| file  | Identifies a file type  |
| find  | Searches for a file  |
| ln  | Creates a symbolic or hard link  |	                              
| ls  | Lists files  |
| mkdir  | Creates a directory  |
| mv  | Renames or moves a file  |
| rm  | Removes a file  |
| touch  | Creates a file or updates a file's timestamp|

## Text Processing and Scripting Commands

| Command  | Description  |
| ------------- | ------------- |
| awk  | The awk general-purpose text processing language  |
| cat  | Displays and concatenates files  |
| cmp  | Compares binary files  |
| cut  | Extracts columns of lines  |
| diff  | Compares text files  |
| echo  | Prints text  |
| egrep  | Extended grep  |
| grep  | Searches for lines matching a regular expression  |
| head  | Displays the first lines of a file  |
| less  | Displays a text file  |
| more  | Displays a text file  |
| patch  | Incorporates changes into files; the opposite of diff  |
| sed  | A stream editor  |
| sort  | Sorts lines in a file  |
| split  | Chops a file into pieces  |
| tail  | Displays the last lines of a file  |
| tee  | Duplicates a file stream  |
| tr  | Translates (or substitutes) characters  |
| uniq  | Removes duplicate adjacent lines  |
| vi  |	A visual full-screen editor  |
| wc  | Counts words, lines, and characters in a file  |
| xargs  | Executes a command repeatedly with arguments from the input stream  |

## Online Documentation Commands

| Command  | Description  |
| ------------- | ------------- |
| info  |	Displays GNU-style documentation  |
| man  | Displays the traditional Unix online manual  |


## Process and System Utility Commands

| Command  | Description  |
| ------------- | ------------- |
| at  |	Runs a program at a certain time  |
| crontab  | Runs a periodic job  |
| groups  | Shows group membership  |
| id  | Shows the current user ID  |
| kill  | Sends a signal to a process  |
| logger  |	Records a message to the system logger  |
| lsof  |	Lists open files and other information  |
| mount  | Attaches a filesystem to a directory tree  |
| passwd  |	Changes a password  |
| printenv  |	Prints environment variables  |
| ps  | Displays processes  |
| reset  | Attempts to reset the terminal  |
| strace  | Traces system calls  |
| su  | Switches users  |
| sync  |	Writes kernel buffers to disk  |
| time  | Displays how much processor and system time a process takes  |
| top  | Shows the processes with the most resource consumption  |
| umount  |	Detaches a filesystem from a directory tree  |
| nsenter  | run program with namespaces of other processes  |


## System Information Commands

| Command  | Description  |
| ------------- | ------------- |
| arch  |	Displays the system architecture  |
| df  |	Displays disk usage statistics  |
| dmesg  | Displays buffered kernel messages  |
| finger  |	Displays user information  |
| free  |	Displays free memory statistics  |
| hostname  |	Displays the current host's name  |
| last  | Shows the last users who logged in  | 
| tty  | Displays the current terminal name  |
| uptime  |	Displays system load and how long the system has been running  |
| uname  | Displays kernel identification information  |
| w  | Displays uptime information and current users  |
| who  | Displays current users  |
| whoami  |	Displays the current user  |


## Archival and Compression Commands

| Command  | Description  |
| ------------- | ------------- |
| bunzip2  | A decompression program  |
| bzip2  | A decompression program  |
| cpio  |	An archival program  |
| gunzip  | A decompression program  |
| gzip  | A compression program  |
| tar  | An archival program  |


## Miscellaneous Utility Commands

| Command  | Description  |
| ------------- | ------------- |
| cal  | Shows a calendar  |
| date  | Displays the current date  |
| pwd  | Prints the working directory  |
| sleep  | Pauses for a specified number of seconds  |
| strings  | Attempts to show any text embedded in a binary file  |
| which  | Displays the first matching program in the current path  |

## Network related commands

| Command  | Description  |
| ------------- | ------------- |
| ifconfig  |	configure a network interface  |
| traceroute  |	print the route packets trace to network host  |
| netstat  | Print network connections, routing tables, interface statistics  |
| tcpdump  | dump traffic on a network  |
| dig  | DNS lookup utility  |
| nslookup  |	query Internet name servers interactively  |
| telnet  |	telnet to a remote host  |
| scp  | secure copy files to/from a remote host  |
| nmap  |	Network exploration tool and security / port scanner  |
| ssh	 | secure shell login to a remote host  |
| ftp  | file transfer to/from a remote host  |
| sftp  |	secure file transfer to/from a remote host  |
| ip  | show / manipulate routing, devices, policy routing and tunnels  |


## Shell Scripting

To convert repetitive jobs into small utilities, we use shell scripting. For example, while debugging we might need to check for a file to have a certain string periodically. For this, we can have a while loop with sleep to make it iterative with repetition.<br/>
<br/>
The following topics need to be learned and practiced to get proficiency in shell scripting.<br/>
<br/>
What is a shell and how a script is executed? 
### 1. Variables
~~~
Variable Names
Defining Variables
Accessing Values
Read-only Variables
Unsetting Variables
Variable Types
Local Variables
Environment Variables
Shell Variables
Special varibles like $?, $# etc.,
~~~
### 2. Arrays
~~~
Defining Array Values
Accessing Array Values
~~~
### 3. Operators
~~~
Arithmetic Operators
Relational Operators
Boolean Operators
String Operators
File Test Operators
~~~
### 4. Decision making
~~~
if...else statement
case...esac statement
~~~
### 5. Loops
~~~
while loop
for loop
until loop
select loop
Nesting loops
Loop control
~~~
### 6. Other
~~~
The break statement
The continue statement
Shell Input/Output Redirections
Functions
Creating Functions
Pass Parameters to a Function
Returning Values from Functions
Nested Functions
Function Call from Prompt
~~~
