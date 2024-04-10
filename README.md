# autoswitch
A functional shell script to do config file refreshment and services restart automatically 
This is a lazy code for a solid requirement, may leads you recall "goto" if you are old enough like me. I wrote it under ubuntu 18.04, should be fine for all other ubuntu versions, if not, some " or ' or [ or { need to be adjusted. 

you can download , edit , change and share the code freely and take risk by your own.

Notice: 
1, if you make your serverlist.txt in windows , pls use 'dos2unix' command to trasnfer it in unit format otherwise the doman name can not be used as expected.  You may need in stall dos2unix by "apt install dos2unix"
2, You may meet sudo password issue if you wanna restart some services require sudo , goodle it, many ways to do it in shell.
3, use cron to set it work hourly , or maybe daily as you wish. "sudo croncab -e" to edit the frequency then restart it. notice the path while execure the sh.
4, until I find out anything more worth to share
