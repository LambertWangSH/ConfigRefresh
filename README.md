# autoswitch
A functional shell script to perform config file refreshment and services restart automatically. Simple function ,revise the string in config file and restart the service. ( in this case, shell will ping different domain , come up the best domain - with the best return time, then replace the domain name in config file ) 
This is a lazy code for a solid requirement, not optimized yet, it worked fine for me , so I decide to share it. You might need to revise path,file name with similar concept.  I wrote it under ubuntu 18.04, should be fine for all other ubuntu versions, if not, some " or ' or [ or { need to be adjusted. 

you can download , edit , change and share the code freely and take risk by your own.

Notice: 
1, if you make your serverlist.txt in windows , pls use 'dos2unix' command to trasnfer it in unit format otherwise the doman name can not be used as expected.  You may need in stall dos2unix by "apt install dos2unix"
2, You may meet sudo password issue if you wanna restart some services require sudo , google it, many ways to do it in shell.
3, use cron to set it work hourly , or maybe daily as you wish. "sudo crontab -e" to edit the frequency then restart it. Revise your path in the file while execure the sh.
4, until I find out anything more worth to share.
