# 3 Linux fundamentals

1. 
list the different types of device files 

* /dev/sda -  
* /dev/sda[number] -  
* /dev/input/mouse0 - 
* /dev/input/event0 - 
* (/dev/snd/*) -  
* /dev/ttyS* -  

2. 
who is in charge of processes
how many processes are running at one time

3. 
what is the system wide env file called

4. 
/bin/:
/boot/:
/dev/:
/etc/:
/home/:
/lib/:
/media/*:
/mnt/:
/opt/:
/root/:
/run/:
/sbin/:
/srv/:
/tmp/:
/usr/:
/usr/local/ 
/usr/share/ 
/var/
/proc/ /sys/

5. 
to unpause a job

6. 
setuid or setgid allows for the buffer overflow hack

7.
what does the __dmesg__ command do 

# 4 Installing Kali 


1. 
what is the GRUB bootloader 

2. 
what is LUKS,LVM 

3.
 how are virtual drivers listed in df 

4.
 troubleshooting tips for the arm installer, where are the logs and the shell



# 5. Configuring Kali 

1. 
does system-networkd support wireless

2. 
list the user acct files in /etc

3. 
who is not limited to /etc/shellls with the chsh command

4. 
in postgres does each cluster have its own port

5. 
in apache whats the .htaccess file for

6. 
what is the main control system in kali

7.
where are the system unit files

8.
what are target units

9.
what does systemd do when you enable a service

10. 
enable and disable work only at next boot True or False


# 6. Helping yourself and getting help 

1.
what are the GUI's for the man pages

2.
list the man page organization 
1
2
3
4
5
6
7
8
9


3. how to file a good bug report

4. if a package is not working well where can you try

5. 
for where to report is debbugs http based or email based ?

# 7 Securing and Monitoring Kali Linux

1. 
what is fail2ban

2. 
can root create a chain in Netfilter 

3. 
name the several chain actions

4. 
what does logcheck do 

5.
where does logcheck put ignored messages?

6.
do system files regularly stay the same

7.
what are some logging and monitoring tools 


# 8 Debian Package Management

1.
list and describe 3 different types of packages

2.
name of file the apt uses when downloading pacakges

3. 
what does processing triggers mean 

4. when will dpkg refuse to install something

5.
wheres the dpkg database

6. 
where are the old packages
whats the difference between clean and autoclean

7.
what does apt-cache dumpavail do 

8.
what are backports

9.
which  files deals with package poilcies

10. 
when can you run *dpkg --remove-architecture [arch]*

11. 
name one req for *Multi-Arch: same*

12.
when a 3rd party is added to the list of packages, explain the process so that admin can trust packages from that 3rd party

13. 
.deb files, binary, control, data which contains vital info about the package

14. 
whats the difference between the control

15.
will dpkg genereate a md5sums if it does not exist in the package?