# LINUX-CUSTOM-SCRIPT

Command name - internsctl
Command version - v0.1.0

To obtain the size of the specified file only, 
command:
xenonstack@xsd-034:~$ internsctl file getinfo --size hello.txt
5448
To obtain the permissions of the specified file only, 
command:
xenonstack@xsd-034:~$ internsctl file getinfo --permissions hello.txt
-rw-r--r--
To obtain the owner of the specified file only, 
command:
xenonstack@xsd-034:~$ internsctl file getinfo --owner hello.txt
xenonstack
To obtain the last modified time of the specified file only, 
command:
xenonstack@xsd-034:~$ internsctl file getinfo --last-modified hello.txt
2020-10-07 20:34:44.616123431 +0530
