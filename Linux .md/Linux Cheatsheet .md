# Linux Cheatsheet
## Basic Commands

    date: It shows the current date and time    
    cal :It shows the current month's calendar    
    uptime :It shows when your system running
    whoami	It will show you
    users	It shows user information
    who	It will show you who you are and your public IP
    man	It will show you command details eg. man who
    ls	It will show files and directories in the current working directory
    ls -a	Shows hidden files
    pwd	Shows the path of the present working directory
    Files and Directories
    Commands	Description
    touch	To create empty files and to update timestamp
    cat > filename	It creates a file and allows to add content
    cat <filename>	Shows the content of the file
    head <filename>	Shows the first top 10 lines of a file
    tail <filename>	Shows the bottom 10 lines of a file
    rm <filename>	Removes file
    rm -rf <filename>	Removes file forcefully
    cp <filname1> <filename2>	It copies the content of a filename1 to filename2
    mv <filename1> <filename2>	It is used to rename or move files.
    mkdir <dirname>	To create a directory
    cd <dirname>	To change the directory
    rm -r <dir name>	Removes directory
    rm -rf <dir name>	Forcefully removes directory
    find	To search files or directories in Linux
    grep	To search patterns in a file
    diff	find the difference between file
    sed	To search and replace content from a file
    
  #   User Management
    
    All the user information is stored in /etc/passwd.

    addgroup <groupname>	It will add a new group
    useradd <username>	It will create a user
    su <username>	To switch user
    deluser <username>	To delete user
    del group <groupname>	To delete a group
    chown	To change ownership of a file
    chgrp	To change group membership of a file
    usermod -g	To change the group of a user
    usermod -a -G	To add a user to multiple groups
    passwd	To change the password
    
# System Management

    history	shows list commands executed by the user
    free	It shows free and used memory in the system
    /proc/meminfo	It shows memory information
    /proc/cpuinfo	It shows CPU information
    uname -a	It shows kernel information
    du	It shows directory-wise disk usage (for memory monitoring)
    df	It shows filesystem disk usage (for memory monitoring)
    top / top	for CPU monitoring
# Software Management
    yum is the tool to install, delete, update and manage RHEL software packages.
    yum install <package name>	It will install the package. eg. yum install git
    yum remove <package name>	It will remove the package
    yum update <package name>	It will update the package
    yum info <package name>	It will give package info
    yum list available	It will show available packages on Yum
    yum list installed	It will show installed packages.

  #  Debian, Ubuntu, and Linux Mint operating systems
    
    apt-get install <package name>	It will install the package
    apt-get remove <package name>	It will remove the package
    apt-get purge <packga name>	It will remove the package and its configuration
    dpkg -l	It will show all installed package
    
# Networking

    ping host	ping host and output result
    hostname	list the hostname of the server
    wget	It will download packages or software on the Linux system
    telnet	connect to the remote host
    curl	access the application from the browser
    
# Services

    service <name of the service> status	To see the status of the service
    service <name of the service> start	Start the service
    service <name of the service> stop	stop the service
    service <name of the service> reload	Reload the service
    service <name of the service> restart	Restart the service
    
# Process Management
    
    ps -ef	To display the current working process
    top	Display all running process
    kill -9	Kill the process
    
# Compression

    gzip file	compress the file and rename it to file.gz
    gzip -d file.gz	Decompresses file.gz back to the file
    tar cf file.tar file	Create a tar named file.tar containing file
    tar xf file.tar	Extract the files from the file.tar
    tar czf file.tar.gz files	Create a tar with Gzip compression
    tar xzf file.tar.gz files	Extract a tar using Gzip compression
