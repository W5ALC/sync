# sync
Termux script to backup various android internal storage folders
the best way to use this is with an ssh config file to allow for easy login e.g. $ ssh home


https://linuxize.com/post/using-the-ssh-config-file/


ssh setting in ~/.ssh/config. similar to this ... if you setup host as home in your config you won't have to change the rsync command

![image](https://user-images.githubusercontent.com/7112421/210189866-dbfeb043-914b-4030-ae6f-d6d2453779cc.png)

after setting up your config file change the folders and locations of your choosing.

the script as is backs up folders in /storage/emulated/0

the folders in $PHONE_LOC(/storage/emulated/0) that are getting backed up are {DCIM,Download,Movies,Music,PDF,Pictures} make changes to which folders you want backed up 

im sorry its not quite as user friendly as it should be 

use this with  Termux:Widget for a nice click and choose backup solution
