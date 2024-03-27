## Module: Introduction To Academy (Tier 0)
**Questions:** What is the name of the first section of this module? If you are using a translation solution while studying, please disable it temporarily to enter the first section's name in English.

**Ans:** Introduction

**Questions:** Based on the commands you executed, what is likely to be the operating system flavor of this instance? (case-sensitive)

**Ans:** parrot

**Questions:** What is the proof text displayed in the Target website you browsed?

**How to find:**

click on target to see the ipaddress with port number
then copy that and put that on a web browser search bar as http://83.136.255.150:57021
you will see "Welcome to HTB Academy! Proof: t4rg3ts"

**Ans:** t4rgts

## Module: INTRODUCTION TO NETWORKING

**Questions:** Submit the decimal representation of the subnet mask from the following CIDR: 10.200.20.0/27

**Ans:** 255.255.255.224

**Questions:** Submit the broadcast address of the following CIDR: 10.200.20.0/27

**Ans:** 10.200.20.31

**Questions:** Split the network 10.200.20.0/27 into 4 subnets and submit the network address of the 3rd subnet as the answer.

**Ans:** 10.200.20.16

**Questions:** Split the network 10.200.20.0/27 into 4 subnets and submit the broadcast address of the 2nd subnet as the answer.

**Ans:** 10.200.20.15

## Module: Linux Fundamentals

**Questions:** Find out the machine hardware name and submit it as the answer. 

**Answer:** x86_64

**Questions:** What is the path to htb-student's home directory? 

**Ans:** /home/htb-student

**Q:** What is the path to the htb-student's mail? 

**Ans:** /var/mail/htb-student

**Q:** Which shell is specified for the htb-student user? 

**Ans:** /bin/bash

**Q:**  Which kernel version is installed on the system? (Format: 1.22.3) 

**Ans:** 4.15.0

**Q:**  What is the name of the network interface that MTU is set to 1500? 

**Ans:** ens192

**Q:** What is the name of the hidden "history" file in the htb-user's home directory? 

**Ans:** .bash_history

**Q:** What is the index number of the "sudoers" file in the "/etc" directory? 

**Ans:** 147627

**Q:**  What is the name of the last modified file in the "/var/backups" directory? 

**Ans:** apt.extended_states.0

**Q:** What is the inode number of the "shadow.bak" file in the "/var/backups" directory? 

**Ans:** 265293

**Q:** What is the name of the config file that has been created after 2020-03-03 and is smaller than 28k but larger than 25k? 

**Ans:** 00-mesa-defaults.conf

**Q:** How many files exist on the system that have the ".bak" extension? 

**Ans:** 4

**Q:**  Submit the full path of the "xxd" binary.

**Ans:** /usr/bin/xxd

**Q:** How many files exist on the system that have the ".log" file extension? 

**Ans:** 32

**Q:**  How many total packages are installed on the target system? 

**Ans:** 737

**Q:**  How many services are listening on the target system on all interfaces? (Not on localhost and IPv4 only)

**Ans:** 7

**Q:** Determine what user the ProFTPd server is running under. Submit the username as the answer. 

**Ans:** Proftpd

**Q:** Use cURL from your Pwnbox (not the target machine) to obtain the source code of the "https://www.inlanefreight.com" website and filter all unique paths of that domain. Submit the number of these paths as the answer. 

**Ans:** 34

**Q:** Which option needs to be set to create a home directory for a new user using "useradd" command?

**Ans:** -m

**Q:** Which option needs to be set to lock a user account using the "usermod" command? (long version of the option)

**Ans:** --lock

**Q:**  Which option needs to be set to execute a command as a different user using the "su" command? (long version of the option) 

**Ans:** --command

**Q:** Use the "systemctl" command to list all units of services and submit the unit name with the description "Load AppArmor profiles managed internally by snapd" as the answer. 

**Ans:** snapd.apparmor.service

**Q:**  What is the type of the service of the "syslog.service"? 

**Ans:** notify

**Q:**  Find a way to start a simple HTTP server inside Pwnbox or your local VM using "npm". Submit the command that starts the web server on port 8080 (use the short argument to specify the port number). 

**Ans:** http-server -p 8080

**Q:** Find a way to start a simple HTTP server inside Pwnbox or your local VM using "php". Submit the command that starts the web server on the localhost (127.0.0.1) on port 8080.

**Ans:** php -S 127.0.0.1:8080

**Q:** How many partitions exist in our Pwnbox? (Format: 0) 

**Ans:** 3

