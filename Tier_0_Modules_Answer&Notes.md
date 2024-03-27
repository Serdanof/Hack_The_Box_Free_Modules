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

## Modules: Network Enumeration with Nmap

**Q:** Based on the last result, find out which operating system it belongs to. Submit the name of the operating system as result. 

**Ans:** Windows

**Q:** Find all TCP ports on your target. Submit the total number of found TCP ports as the answer. 

**Ans:** 7

**Q:** Enumerate the hostname of your target and submit it as the answer. (case-sensitive) 

**Ans:** NIX-NMAP-DEFAULT

**Q:** Perform a full TCP port scan on your target and create an HTML report. Submit the number of the highest port as the answer. 

**Ans:** 31337

**Q:** Enumerate all ports and their services. One of the services contains the flag you have to submit as the answer.

**Ans:** HTB{pr0F7pDv3r510nb4nn3r}

**Q:** Use NSE and its scripts to find the flag that one of the services contain and submit it as the answer. 

**Ans:** HTB{873nniuc71bu6usbs1i96as6dsv26}

**Q:** Our client wants to know if we can identify which operating system their provided machine is running on. Submit the OS name as the answer. 

**Ans:** Ubuntu

**Q:** After the configurations are transferred to the system, our client wants to know if it is possible to find out our target's DNS server version. Submit the DNS server version of the target as the answer. 

**Ans:** HTB{GoTtgUnyze9Psw4vGjcuMpHRp}

**Q:** Now our client wants to know if it is possible to find out the version of the running services. Identify the version of service our client was talking about and submit the flag as the answer. 

**Ans:** HTB{kjnsdf2n982n1827eh76238s98di1w6}

## Module: Introduction to Active Directory

**Q:**  What Active Directory structure can contain one or more domains? 

**Ans:** forest

**Q:** True or False; It can be common to see multiple domains linked together by trust relationships? 

**Ans:** True

**Q:** Active Directory provides authentication and <____> within a Windows domain environment. 

**Ans:** Authorization

**Q:** What is known as the "Blueprint" of an Active Directory environment? 

**Ans:** schema

**Q:** What uniquely identifies a Service instance? (full name, space-separated, not abbreviated) 

**Ans:** Service Principal Name

**Q:** True or False; Group Policy objects can be applied to user and computer objects. 

**Ans:** True

**Q:** What container in AD holds deleted objects? 

**Ans:** Tombstone

**Q:** What file contains the hashes of passwords for all users in a domain? 

**Ans:** NTDS.DIT

**Q:**  True or False; Computers are considered leaf objects. 

**Ans:** True

**Q:**  <___> are objects that are used to store similar objects for ease of administration. (Fill in the blank) 

**Ans:** Organizational Units

**Q:** What AD object handles all authentication requests for a domain? 

**Ans:** Domain Controller

**Q:**  What role maintains time for a domain? 

**Ans:** PDC Emulator

**Q:** What domain functional level introduced Managed Service Accounts? 

**Ans:** Windows Server 2008 R2

**Q:** What type of trust is a link between two child domains in a forest? 

**Ans:** Cross-link

**Q:**  What role ensures that objects in a domain are not assigned the same SID? (full name) 

**Ans:** Relative ID Master

**Q:**  What networking port does Kerberos use? 

**Ans:** 88

**Q:** What protocol is utilized to translate names into IP addresses? (acronym) 

**Ans:** DNS

**Q:** What protocol does RFC 4511 specify? (acronym) 

**Ans:** LDAP

**Q:**  What Hashing protocol is capable of symmetric and asymmetric cryptography? 

**Ans:** Kerberos

**Q:** NTLM uses three messages to authenticate; Negotiate, Challenge, and <__>. What is the missing message? (fill in the blank) 

**Ans:** Authenticate

**Q:** How many hashes does the Domain Cached Credentials mechanism save to a host by default? 

**Ans:** 10

**Q:** True or False; A local user account can be used to login to any domain connected host. 

**Ans:** False

**Q:** What default user account has the SID "S-1-5-domain-500" ? 

**Ans:** Administrator

**Q:** What account has the highest permission level possible on a Windows host 

**Ans:** SYSTEM

**Q:** What user naming attribute is unique to the user and will remain so even if the account is deleted? 

**Ans:** ObjectGUID

**Q:** What group type is best utilized for assigning permissions and right to users? 

**Ans:** Security

**Q:** True or False; A "Global Group" can only contain accounts from the domain where it was created. 

**Ans:** True

**Q:** Can a Universal group be converted to a Domain Local group? (yes or no) 

**Ans:** Yes

**Q:**  What built-in group will grant a user full and unrestricted access to a computer? 

**Ans:** Administrators

**Q:** What user right grants a user the ability to make backups of a system? 

**Ans:** SeBackupPrivilege

**Q:**  What Windows command can show us all user rights assigned to the current user? 

**Ans:** whoami /priv

**Q:** Confidentiality, <___>, and Availability are the pillars of the CIA Triad. What term is missing? (fill in the blank) 

**Ans:** Integrity

**Q:** What security policies can block certain users from running all executables? 

**Ans:** Application Control Policies

**Q:** Computer settings for Group Policies are gathered and applied at a <___> minute interval? (answer is a number, fill in the blank ) 

**Ans:** 90

**Q:**  True or False: A policy applied to a user at the domain level would be overwritten by a policy at the site level. 

**Ans:** False

**Q:** What Group Policy Object is created when the domain is created? 

**Ans:** Default Domain Policy

**Q:** Once you have finished the tasks, type "COMPLETE" to move on. 

**Ans:** COMPLETE

**Q:** Once you have finished the tasks, type "COMPLETE" to move on. 

**Ans:** COMPLETE




