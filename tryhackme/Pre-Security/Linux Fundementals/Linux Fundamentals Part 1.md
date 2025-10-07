# TryHackMe: [Linux Fundamentals Part 1]

**Date Started:** 2025-10-04  
**Module Pathway:** Pre Security 
**Objective:** [BEgin learning Linux CLI]

---

## 🧠 Notes
- Task 4; Running your firsdt few commands
Began by starting with simple commands to get used to the CLI. echo, whoami. when using echo, a single word can be outside the "".      However, once the string is longer, it must be encased in "".

- Task 5; Interacting With the Filesystem.
There are a few commands useful in the navigating the filesystem such as ls for listing the files and directories, cd to change directories, cat which is used to show what is in files or to combine files, and pwd, which prints teh working directory.

- Task 6; Searching for files
We can use find command to look for files that we know exist, or that have a certain file extension. Grep is used to look through contenets of files and find specific values. 

- Task 7; An Introduction to Shell Operators
There are a lot of operators that are useful in Linux that allow us to do a few extra things. 
& allows commands to be executed in the background, allowing us to continue working. && allows us to connect commands together. 
com1 && com2, note that com2 will only run if com1 is successful. ">" is used to redirect commands. echo hey > welcome will create a file called welcome, with the contents of hey. 

## Commands
- echo "" ; outputs the text that follows.
- whoami ; will show which user you are currently logged in with.
- ls ; list files and directories.
- cd ; change directory.
- cat ; view or combines files.
- pwd ; print working directory.
- find ;  find files
    find -name "" will find a specific file.
    find -name *.xxx will find all extensions of this kind.
- grep ; find specifics in files
- & ; execute commands in the background 
- && ; run comands together
- ">" ; redirect commands
- ">>" ; redirects, however puts information at the end of the file, not overwrite it.