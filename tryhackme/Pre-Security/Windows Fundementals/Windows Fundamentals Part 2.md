# TryHackMe: [Windows Fundamentals Part 2]

**Date Started:** 2025-10-04  
**Module Pathway:** Pre Security 
**Objective:** [Bsic Windows Navigation(reminder)]
**Important** Some tasks are not completed due to either lacking of notable information, or simply as simple discussions.
---

## 🧠 Notes
- Task 1 ; Introduction and starting virtual machine

- Task 2 ; Sytem Configuration
MSConfig is an advanced troubleshooting utility for diagnosing startup issues primarily.
It has 5 tabs to work through
    General
    Boot
    Services
    Startup
    Tools   

- Task 4 ; Computer management   
Computer management has three sections; System Tools, Services and Applications.
    System Tools 
        Task Scheduler is used to create automated jobs to run automatically.
    Event Viewer
        Allows us to view ecvents that have  occured on the computer, like logs.
    Device Manager 
        Allows us to see which devices are connected to the machine
    Storage holds Windows Server Backup and Disk Managment
        Disk Management is a utility to set up new drives, extend/shrink partitions, change and assign drive letters.
    Services and Applications
        Services are special applications that run in the background, such as vanguard anti cheat for Riot Games.

- Task 5 ; System Information
System Information (msinfo32) shows Hardware Resources, Components and Software Enviroment. This area shows intense level of information about the machine.

- Task 6 ; Resource Monitor
Resource MOnitor allopws you to view the load on specific parts of the machine in detail, areas such as CPU, RAM, Disk and Network.

- Task 7 ; Command Prompt
Command Prompt (CMD) is windows CLI to interact with the operating system without the GUI. Through use of commands you can achieve information quickly without hassle (if the commands are known.) 
ipconfig is much quicker than having to right click and navigate the GUI to find an IP address and Subnet. 
netstat is used to see what TCP/IP connections are currently ongoing, including state and ip addresses. 

- Task 8 ; Registry Editor
Windows REgistry is a database used to store information necessary to configure the system for one or all users.
The Reg Editor is an advanced area that can break systems easily if messed with without understanding.

## Commands
- hostname ; shows the name of the computer
- whoami ; shows the user you are logged in with
- ipconfig ; shows network settings
- /? ; is the help command
- cls ; clear the terminal
- netstat ; this will show TCP/IP network connections