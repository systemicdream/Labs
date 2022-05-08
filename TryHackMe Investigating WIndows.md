# TryHackMe Investigating WIndows

1. used the System section in control panel to find the os version
2. used the get-localuser command to find the last log on for the computer
3. shown with get-localuser
4. used the startup registry to find the application that launched on startup to find the ip
5. used computer management to find the users with admin access 
6. check the scheduled tasks and found that clean file system was malicous
7. looked at the task details to find it was trying to open ns.ps1
8. found the port on the same page
9. went back to the get-localuser info to find they have never logged on
10. used event viewer and the event id to find the time
11. looked into the files of the malwares files to find it was mimikatz
12. used the hosts file to find the address
13. found the extension in a file called tests in wwwroot
14. used firewall to find the port
15. used the website listed in the hosts file