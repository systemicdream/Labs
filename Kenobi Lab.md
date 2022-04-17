# Kenobi Lab

## Task 1

did a nmap scan to find out the number of open ports

## Task 2

used nmap scripts to look for info about smb. find 3 smb shares. use smbclient utility to find log.txt. Used nmap script to see the /var directory

## Task 3

found the version of ProFtpd. Found the number of exploits ProFTPd is running. Mounted the network on the virual machine and used that to find the user flag. 

## Task 4

used a script to search the system for certain binaries and found /usr/bin/menu to be out of the ordinary. after running the binary 3 options appear. use strings to see the strings of the binary. find an exploit that would allow this binary to use root permissions.