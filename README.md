# Linux-Commands

1. sudo command
sudo: Shot for superuser do, this is used to perform tasks that requires administartive or root permissions

sudo apt update
Alt text

2. pwd command
pwd means "Print Working Directory". This command is used to find the path of your current /present working directory.

pwd
pwd [-L]
pwd [-P]
pwd [-LP]
Alt text

3. cd command
cd CommandLinux
cd ~
cd -
cd ..
4. ls command
ls CommandLinux
ls -R
ls -a
ls -lh
5. cat command
cat sqlite_commands.sh
cat filename1.txt filename2.txt > filename3.txt
tac filename3.txt
6. cp command
cp sqlite_commands.sh /home/kingsley/unixcommands/
cp filename1.txt filename2.txt filename3.txt /home/kingsley/Documents/
7. mv command
mv sqlite_commands.txt /home/kingsley/unixcommands
mv DevOps /home/kingsley/Downloads/
8. mkdir command
mkdir Album
mkdir Album/List
9. rmdir command:
This command is used to permanently delete an empty directory.

rmdir Album/List
10. rm command:
This command is used to delete files within a directory.

rm Linux
rm filename1.txt filename.txt2 filename3.txt
11. touch command:
touch Linux
12. locate command:
touch Linux
13. find command:
This command is used to find a file or folder within a directory.

find /home -name CommandLinux
14. grep command:
This command is used to find a word by searching through all the texts in a specific file.

grep values CommandLinux
15. df command:
This command is used to report the system disk space usage.

df -h
16. du command:
This command is used to check how much space a file or a directory takes up.

du /home/kingsley/CommandLinux
17. head command:
This command allows you to view the first 10 lines in a text.

head DevOps
18. tail command:
This command allows you to view the last 10 lines of a file. It shows whether a file has a new data or read error messages.

tail DevOps
19. diff command:
This command is used to compare two contents of a file line by line. After analyzing them, it will display the part that do not match.

diff DevOps Linux
diff -c DevOps Linux
20. tar command:
This command is used to archive multiple files into a TAR file. A common Linux format similar to ZIP.

tar -cvf filename1.txt.tar /home/kingsley
File Permissions and Ownership
21. chmod command:
This is a command that modifies a file or directory's read, write and execute permissions.Each file in Linux is associated with 3 user classes - Owner, group member, and others.

ls -ltr
chmod 777 DevOps  
chmod 777 LinuxCommand
22. chown command:
This is used to change the ownership of a file, directory or symbollic link to a specified username.

chown kingsley Linux
23. jobs command:
This command will display all the running processes along with their statuses. This command is only available in csh, bash, tcsh, and ksh shells.

job jobID
24. kill command:
This command is used to termite an unresponsive program manually by identifying the application's PID number. This will signal misbahaving applications and instruct them to close their processes. To check their PID Number, please run the command below.

ps ux
To terminate the program, please type the below command.

kill SIGKILL PID
25. ping command:
This command is used to check if a network or server is reachable. This is mostly used to troubleshoot connectivity issues.

ping google.com
26. wget command:
This command allows you to download files from the internet using the wget command. This works without hindering any running processes.

wget https://wordpress.org/latest.zip 
27. uname command:
This is either called uname or unix name. A command that prints detailed information about your Linux system and hardware, inclusive of the machine name, Operating System, and Kernel.

uname -a
uname -s
uname -n
28. top command:
This command is used to display all running processes and a dynamic real-time view of the current system.

top
29. history command:
With history, the system will list up to 500 previously executed commands allowing you to reuse them without re-entering.

history
30. man command.
this command will provide the user manual of any command or utilities you can run in the terminal including name, description and options.

man ls
man 2 ls
31. echo command.
This command is a built in utility that displays a line of text or string using the standard output.

echo "How are you?"
echo \A DevOps
echo -e DevOps
echo -n DevOps
32. zip, unzip commands:
This command will compress files and directories into a zip file, to archive or reduce disk space usage.

zip archive.zip blog
zip archive.zip text
unzip archive.zip
33. hostname command:
This command will show the system's hostname or ip address

hostname
hostname -i
hostname -A
hostname -alias
34. useradd, userdel command
The useradd command will create a new account the passwd command allows you to add a password

sudo useradd Kelvin
Before I proceed to create a password for Kelvin, I have to type in sudo -i, and then type, id Kelvin

sudo passwd Kelvin 
To delete the user

userdel John
To return back to the previous user account, run the "exit" command, then run "logout"

35. apt-get command
This command handles advanced package tools (APT) in Linux. It lets you retrive information and bundles from authenticated sources.

apt-get update
sudo apt-get update
36. nano, vi, jed commands:
The nano command denotes keywords and can work with most languages.

nano DevOps
The vi command works in two modes insert and command: this can edit and create a text file perform operations such as copying, saving, openig and pasting a file.

vi Linux
The jed has a dropdown interface that allows users to perform tasks without entering keyboard combinations or commands.

jed Linux
37. alias, unalias command
This command allows you to create a shortcut with the same functionality as a command, file name or text.

alias dv='DevOps'
The unalias command deletes an existing alias

unalias dv
38. su command:
This command allows you to switch user or run a program as a different user. It is beneficial for accessing the system through SSH or GUI display when root user is unavailable.

su
39. htop command:
This command monitors system resources and server processes htop command has additional features and improvements than the top command. Before you can run the below command, you have to install the htop service using the command "sudo snap install htop" or "sudo apt install htop".

htop -d
htop -C
htop -h
40. ps command:
This command produces a snapshot of all the processes on your system.

ps -T
ps -u
ps -A
ps -e
THANK YOU!


