## Commands 
## Linux Fundamentals 1
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
## Linux Fundamentals 2
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
- su ; switch users
## Linux Fundamentals 3
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