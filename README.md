# sync
Termux script to backup various android internal storage folders
the best way to use this is with an ssh config file to allow for easy login e.g. $ ssh home

ssh setting in ~/.ssh/config.

Host home
  HostName 192.168.x.x
  User username
  Port 10022
  
  
after setting up your config file change the folders and locations of your choosing.

im sorry its not quite user friendly as it should be 

use this with  Termux:Widget for a nice click and choose backup solution

curl https://raw.githubusercontent.com/W5ALC/sync/sync >/data/data/com.termux/files/usr/bin/syncr && chmod +x /data/data/com.termux/files/usr/bin/syncr && syncr
