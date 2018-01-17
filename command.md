# Installing Bash on Windows 10  
***  
1. Select the developer mode in the Developer tab in the "windows update settings"  
2. After confirming "Windows subsystem for Linux" in the "window operation tuning/off", reboot  
3. Enter bash in cmd  
# bash shell  
***
file delete : `find /root -name 'file' -exec rm -r {} \;`  
error : the program 'rpm' is currently not installed  
`sudo apt install rpm`  
error : the program 'yum' is currently not installed  
`sudo apt install yum`  
error : no acceptable C compiler found in $PATH  
`apt-get update`  
`apt-get upgrade`
`sudo apt-get install build-essential`

