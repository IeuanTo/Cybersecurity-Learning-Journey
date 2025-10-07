# TryHackMe: [Linux Fundamentals Part 1]

**Date Started:** 2025-10-04  
**Module Pathway:** Pre Security 
**Objective:** [BEgin learning Linux CLI]

---

## 🧠 Notes
- Task 1 ; Introduction to module

- Task 2 ; Accessing Your Linux Machine Using SSH (Deploy)
introduction to the use of Secure Shell (SSH) to access machines. SSH is a protocol ised to connect to a machine using encryption. 

- Task 3 ; Flags and Switches
most commands can have an argument follow, using "-" as the start followed by words known as flags or switches. for instance, ls -a will list all files in the directory. using --help we can learn what flags and switches can be used to in conjunction with used command. we can use "man" to open a manual about the required command, to learn more about how to use the command and the best suited flag for the job we are doing.

- Task 4 ; Filesystem Interaction Continued
There are many commands used to make, move and delete files and directories in linux (listed in commands) which make life easier with general maintenance of the filesystem. tip for future: we can provide full file paths for any of the commands.

- Task 5 ; Permissions 101
When using ls -l, it shows 10 columns with drwx as values. These values relate to read, write and execute. 

## Commands
- ssh ; connect to machine with encryption
    ssh "username"@x.x.x.x
- ls -a ; list all files
- ls -l ; list the files vertically like an actual list
- "--help" ; lists all the available flags and switches
- man ; open the manual for a command e.g. man ls
- touch ; creat a file
- mkdir ; makes a directory/creates a folder
- cp ; copy a file or folder
- mv ; move a file or folder
- rm ; remove a file or folder
- file ; determine the type of file