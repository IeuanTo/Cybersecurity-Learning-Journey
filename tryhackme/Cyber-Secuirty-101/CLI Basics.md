# TryHackMe: [Windows CLI]

**Date Started:** 2025-10-11  
**Module Pathway:** Cyber Secrurity 101 
**Objective:** [Learning Windows CLI Basics]

**Reflection** 
*The CLI can achieve what the GUI can in a much quicker and more efficient way. It allows an abundance of information to be gathered, and even changed, without having to change windows constantly*
---

## 🧠 Notes
- Task 1 ; Introduction to module

- Task 2 ; Basic System Information
We can use CLI to quickly gather or change information related to the system. "set" is used to define currently set enviroment variables. we can use ver to quickly show the version of the OS and systeminfo to gather a lot of information about the system. These 3 commands show relatively easy to read information quicly.

- Task 3 ; Network Troubleshooting
Instead of using GUI to find networking information, we can use the CLI. Lots of commands give easy to read and quick access to information. Network troubleshooting begins here with commands such as ping and tracert. nslookup and netstat are other commands that allow troubleshooting a network.

- Task 4 ; File and Disk Management
The file system can be navigated and modified all from CLI using a bunch of commands, cd, dir, mkdir, rmdir, type, more, copy, move and del/erase.

- Task 5 ; Task and Process Management
we can use CLI to see running tasks on the machine. Using commands in CLI will allow us to find the running processes PID and then have the ability to end the process.

## Commands
- set ; show current enviromental variables
    set [vraiable] ; shows the specific variable
    set [variable] + [value] ; changes/creates a variable value
- ver ; shows the current OS version
- syteminfo ; show system information
- ipconfig ; shows brief of network configuration
    ip config /all ; shows the entire network configuration
- ping ; send ICMP packet with echo request and response
- tracert ; packet sent with TTL for each expected router with a echo response for the destination
- nslookup ; looks up host or domain and returns IP address
- netstat ; this will show TCP/IP network connections
    netstat +   -a displays all established connections and listening ports
                -b shows the program associated with each listening port and established connection
                -o reveals the process ID (PID) associated with the connection
                -n uses a numerical form for addresses and port numbers
- cd ; change directories
    cd .. ; up one level
    cd \ ; goes to root of directory
- dir ; list the current child directories
    dir /a ; displays hidden/system files
    dir /s ; Displays files in the current directory and all subdirectories
- mkdir ; creates a directory (folder)
    [mkdir directory_name]
- rmdir ; removes a directory
    [rmdir directory_name]
- type ; view a file
- more ; view a larger file
- copy ; copy a file to a different location
    copy example_file example_file_copy
- move ; moves a file to a new location
    move example_file ..
- del/erase ; deletes a file
- tasklist ; show runnning processes
    tasklist */FI* "imagename eq sshd.exe" ;  sets the filter
- taskkill /PID target_pid ; will kill the process
- shutdown /s ; shutdown system
- shutdown /r ; restart system
- shutdown /a ; abort shutdown process


