1) B
2) BIOS : - makes use of MBR 
          - doesn't have secure boot 
          - supports a maximum of 2TB storage 
   submissions
   UEFI : - makes use of GPT 
          - Has secure boot 
          - supports more than 2TB storage 
3) ```lsmod```
   ``` modprobe dummy ```

4) /proc: contains information about the currently running processes and kernel messages. 
   /sys: contains kernerl libraries and kernel files.

   
5) C and B 
6)Differnces between apt and dpkg
apt: advanced package mangement tool
     which is user friendly
     apt allows resolving of package  dependencies 
dpkg : low level package management tool
       none user friendly
       dpkg does not allow resolving of package dependencies

 7) apt-get full upgrade  

8)  

9) B

10) cat /var/log/syslog | grep error|  wc -l

11) Hard Links : A hard link is an exact copy of the source file changes made in the source file take effect on the hard link.
    A hard link has the same inode as the source file.
    It can be created only for files in thesame filesystem.
    If the source file is deleted the hard link will still exist with all the contents of the source file .
    It is created with the command ``` ln <sourcefile> <hardlink>```

    soft links : A soft link is a short cut to the original file once the file is deleted the soft link points to nothing. soft links also link to directories and can be created for files across different file sytems.
    command ```ln -s <sourcefile> <hardlink>```
 
  12) ```find /etc -type f -name "*.conf*" ntime -7```
  
  13) The cron daemon is used to execute scheduled tasks    
      ```0 0 * * * backup.sh``` 

 14)  B
 15) ```blkid``` 
 16)  ext3 : Older file system supports files up to 2TB. 
     supports 32bits of data
       ext4 : it is a 64bits filesytem newer which supports files larger than 2TB with increased reliablity more reliable.
      supports really large filesytem volumes and is a feature of newer versions of linux operating systems.

18) /etc/fstab file displays file system information,mount points, the filesystem type and uuids

  

19) The BIOS does a Power-On-Self-test checks the state of the hard components
    The bootloader then loads the kernel to memory
    The kernel takes over the operating system boot process
    then the initialisation process starts which is either the sysVinit . 




      
     
