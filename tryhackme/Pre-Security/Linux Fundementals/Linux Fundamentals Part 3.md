# TryHackMe: [Linux Fundamentals Part 1]

**Date Started:** 2025-10-04  
**Module Pathway:** Pre Security 
**Objective:** [Begin learning Linux CLI]

---

## 🧠 Notes
- Task 1 & 2 ; Introduction to module

- Task 3 ; Terminal Text Editors
Nano is an easy to use text editor built into linux, it can also be used to create files by using "nano filename". This also comes wiht a lot of options inside the editor to do extra bits, such as help, search, cut and paste. vim is an advanced text editor with a lot of changeable aspects, such as the commands used to search cut or paste. 

- Task 4 ; General/Useful Utilities
wget is a way to download files through http as if you were in the browser. wget `https://address-in-here.com`. 
You can transfer files from a host machine using Secure Copy or SCP. This allows you to move files between two machines. 
    scp file.txt user@destination:where you want it

-Task 5 ; Processes 101
Processes are programms that run on the machine. They are labled with PID X, an the X being the position of the process. These are shown using ps for individual user processes, or ps -aux for all processes. 
top is used to see real time statistics on the processes ongoing.
kill is used to end processes, using kill followed by a process PID will end it. 
    using SIGTERM, SIGKILL and SIGSTOP, will send a signal to end a process with some specifics.



## Commands
- nano ; text file editor
    nano + "filename" ; will creat a text file
- vim ; an advanced text editor
- wget ; download files
- scp ; transfer files between machines
- ps ; show running processes
    ps -aux ; shows all running processes by other users
- top ; real time statistics on process
- kill ; end a task
    SIGTERM ; kill a process with some cleanup
    SIGKILL ; kill a process with no cleanup
    SIGSTOP ; stop or suspend a process
- systemctl ; start, stop, enable and disable processes : example systemctl [option] [service]
- fg ; beings a process to the foreground
