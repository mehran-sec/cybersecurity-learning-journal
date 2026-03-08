# Basic Commands  

## Access control

Root user have uid 0 and gid 0 and can access all the files because it have ownership of all the files 

linux uses these to grant access to other users 
- users 
- Groups
- File Permissions
we add  secondary groups to users to give them more previlages so they can acces the files that the groups own   i.e  sudo , docker etc
## File 
- sudo chmod  765 [filename]  
To change file prmissions

 - chown username  : Groupname [File name ]
To change **ownership** of file 


## Users and Groups

- *sudo useradd [user name]*
- *sudo groupadd [group name]*

- *sudo usermod -g  Groupname : Username*  
    To change user ***primary***  group 

- *sudo usermod  -aG  Groupname : Username* 
     To add user to **secondary** group ( append 'a' is very important if not used will replace all secodary groups with new one )

- *sudo gpasswd -d Username Groupname* 
      To **remove** user from group 

# Difference in Linux and Windows 
  - linux has monolithic kernal means it also handles the drivers while window have library for it 
  - The file system :
       The  linux has filesystem standard Hiearchy ( FSH ) means it have one root dierechtory and then
        other file or drives  are  branches while in windows each drive is totaly  separate entity as C,D F. 
  - Every thing in linux is file and comes under  the root dierechtory 


# User group 
usrmod username groupname
