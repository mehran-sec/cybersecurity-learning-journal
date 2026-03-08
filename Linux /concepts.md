## Multiple users 
Linux is made for multiple users it has
* Root user  // special control
* other users 
*    In linux we dont need to install drivers they are actually built in the kernal


*     initially the file belong to the user who created no matter where he created it 
      root can create files in User like kali home directory and it would belong to root
## Access Control
**Giving user a permission via groups**  
 - All the files like cdrom  , sudo , amd  , video , audio , blutooth , plugdev in linux are mostly owned by root user thats why root user have all permissions
    to control these devices  
       Now to give these permission to normal user we add the groups of those devices as the secondary group of users 
         sudo usermod - aG groupname username 
## File system : 
* Linux has one root directory ( / )and then other sub directories/sub folders 
 *  Every thing in linux is file even the Devices like Ram ,disk , USB and others 
 *  The commands we use are actually a program in file that gets executed 
     e.g  ls   cd  pwd  mkdir etc 

 * Sub Directories includes 
     
         **root**      // Directory for root user   
        **home**  // directory for normal users 
        **Bin & Sbin** // Directory where programs for commands like                            ls cd pwd etc .. are stored
         **etc** // Editable Text configuration .ALL system
                   configuration file are stored here 
                   Have more subdirectories like 
                   - passwd // to store user information
                   - group // to store group information
                   - shadow // to store encrypted passwords

         **opt** // Directory that store the files that are meant to
                 shared across all users
         
