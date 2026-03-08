# Commands  

# Difference in Linux and Windows 
  - linux has monolithic kernal means it also handles the drivers while window have library for it 
  - The file system :
       The  linux has filesystem standard Hiearchy ( FSH ) means it have one root dierechtory and then
        other file or drives  are  branches while in windows each drive is totaly  separate entity as C,D F. 
  - Every thing in linux is file and comes under  the root dierechtory 
# File Permissions   
  - As linux was built for multiple users so it has permission system for each file 
  - Permissons like rwx . read (r) write(w) execute (x)
  - 1      2      3 
  user (u)    group(g)   others (o)
command :
chmod u=rwx  [fn]  chmod g=rwx  [fn]  chmod o=rwx [fn]
chmod 777 [filename] would change for all users  ( 7=rwx ,  6=rw , 5=rx , 4=r , 3=WX , 2=W , 1=X)
# File Ownership 
chown user:Group [File name ]

# User group 
usrmod username groupname
